SET(SOURCES screens/ui_helloscreen.c
    screens/ui_viplogin.c
    screens/ui_orderscreen1.c
    screens/ui_manageloginscreen.c
    screens/ui_orderscreen2.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    images/ui_img_1852348671.c
    images/ui_img_1485140228.c
    images/ui_img_1429700948.c
    images/ui_img_221393495.c
    images/ui_img_1284172916.c
    images/ui_img_682017832.c
    images/ui_img_1926326647.c
    images/ui_img_1341173067.c
    images/ui_img_293691247.c
    images/ui_img_734771989.c
    images/ui_img_1855500935.c
    images/ui_img_2092529074.c
    images/ui_img_lastpage_png.c
    images/ui_img_nextpage_png.c
    images/ui_img_1609717271.c
    images/ui_img_112040420.c
    images/ui_img_403749227.c
    images/ui_img_1181513690.c
    images/ui_img_139154128.c
    images/ui_img_1119412587.c
    images/ui_img_1143013810.c
    images/ui_img_412946995.c
    images/ui_img_814352610.c
    ui_temporary_image.c
    fonts/ui_font_chinese30.c
    fonts/ui_font_chinese20.c)

add_library(ui ${SOURCES})
