Wi-Fi
=====

概述
--------

`Instructions`_

.. _Instructions: ../template.html

应用程序示例
-------------------

示例代码 `esp-idf-template <https://github.com/espressif/esp-idf-template>`_ 展示了如何将 ESP32 模块连接到 AP。

API 参考手册
-------------

头文件
^^^^^^^^^^^^

  * :component_file:`esp32/include/esp_wifi.h`

宏
------

.. doxygendefine:: WIFI_INIT_CONFIG_DEFAULT


类型定义
----------------

.. doxygentypedef:: wifi_promiscuous_cb_t
.. doxygentypedef:: esp_vendor_ie_cb_t

函数
---------

.. doxygenfunction:: esp_wifi_init
.. doxygenfunction:: esp_wifi_deinit
.. doxygenfunction:: esp_wifi_set_mode
.. doxygenfunction:: esp_wifi_get_mode
.. doxygenfunction:: esp_wifi_start
.. doxygenfunction:: esp_wifi_stop
.. doxygenfunction:: esp_wifi_connect
.. doxygenfunction:: esp_wifi_disconnect
.. doxygenfunction:: esp_wifi_clear_fast_connect
.. doxygenfunction:: esp_wifi_deauth_sta
.. doxygenfunction:: esp_wifi_scan_start
.. doxygenfunction:: esp_wifi_scan_stop
.. doxygenfunction:: esp_wifi_scan_get_ap_num
.. doxygenfunction:: esp_wifi_scan_get_ap_records
.. doxygenfunction:: esp_wifi_sta_get_ap_info
.. doxygenfunction:: esp_wifi_set_ps
.. doxygenfunction:: esp_wifi_get_ps
.. doxygenfunction:: esp_wifi_set_protocol
.. doxygenfunction:: esp_wifi_get_protocol
.. doxygenfunction:: esp_wifi_set_bandwidth
.. doxygenfunction:: esp_wifi_get_bandwidth
.. doxygenfunction:: esp_wifi_set_channel
.. doxygenfunction:: esp_wifi_get_channel
.. doxygenfunction:: esp_wifi_set_country
.. doxygenfunction:: esp_wifi_get_country
.. doxygenfunction:: esp_wifi_set_mac
.. doxygenfunction:: esp_wifi_get_mac
.. doxygenfunction:: esp_wifi_set_promiscuous_rx_cb
.. doxygenfunction:: esp_wifi_set_promiscuous
.. doxygenfunction:: esp_wifi_get_promiscuous
.. doxygenfunction:: esp_wifi_set_config
.. doxygenfunction:: esp_wifi_get_config
.. doxygenfunction:: esp_wifi_ap_get_sta_list
.. doxygenfunction:: esp_wifi_set_storage
.. doxygenfunction:: esp_wifi_set_auto_connect
.. doxygenfunction:: esp_wifi_get_auto_connect
.. doxygenfunction:: esp_wifi_set_vendor_ie
.. doxygenfunction:: esp_wifi_set_vendor_ie_cb


