<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path class="xu_kaabou"/><path fill="url(#iA4m5id)" class="gd4uyvbey"/><path fill="url(#i3Hkb6M)" class="gd4uyvbey"/><g filter="url(#iHKl1ep)"><path class="vc_j-ab_f"/></g><path fill="url(#i0PR2Ic)" class="q0_flrbub"/><path fill="url(#inI9vIb)" class="e3xgskbhi"/><path fill="url(#iri0tkb)" class="mconsebpi"/><path fill="url(#ioLyAEc)" class="mconsebpi"/><g filter="url(#iMbLhhe)"><path class="tlve2kzem"/></g><path fill="url(#itg9jkc)" class="rxr7ftbpw"/><path fill="url(#itg9jkc)" class="rxr7ftbpw"/><path fill="url(#i4X8l2G)" class="rxr7ftbpw"/><path fill="url(#iUcPMVc)" class="x57j-7b1f"/><path fill="url(#ixqOaGF)" class="x57j-7b1f"/><path fill="url(#iPOCpib)" class="bs_5n4vkk"/><path fill="url(#i8GzTPt)" class="bs_5n4vkk"/><path fill="url(#i53VEmc)" class="tly2-yyal"/><g filter="url(#iEMTOfb)"><path class="mf_46vu0u"/></g><path fill="url(#iC2tvPd)" class="jzgc8si5q"/><path fill="url(#ibInzae)" class="jzgc8si5q"/><path fill="url(#ioJ6cvc)" class="jzgc8si5q"/><g filter="url(#i340RoR)"><path class="d7c-wnbhm"/></g><path fill="url(#ifB5Nyd)" class="vv04up0mj"/><path fill="url(#iqF4uMd)" class="vv04up0mj"/><path fill="url(#ig1RupT)" class="vv04up0mj"/><g filter="url(#i9agWfd)"><path class="f1y5xoijx"/></g><path fill="url(#irGYSSc)" class="zuoybg3sf"/><path fill="url(#iF2aybA)" class="zuoybg3sf"/><g filter="url(#iOfOxse)"><path class="xdmz11brs"/></g><path fill="url(#iuOBVOd)" class="ysza622gu"/><path fill="url(#iweSVXd)" class="ysza622gu"/><path fill="url(#idzw08d)" class="ysza622gu"/><path class="zdv_i-bwc"/><path fill="url(#is94T2d)" class="bg8prvb4b"/><path fill="url(#iRNfQMd)" class="bg8prvb4b"/><g filter="url(#iY2KEdd)"><path stroke="url(#im6tpRv)" class="pcwpw8gsa"/></g><g filter="url(#iZolOKc)"><path fill="url(#iCF2t9b)" class="ibtrv6u-z"/></g><g filter="url(#iPB73vc)"><path stroke="url(#is8jkKb)" class="tczwdqbbd"/></g><g filter="url(#iBcR0jP)"><path stroke="url(#ixGlJMb)" class="xfpaktsqo"/></g><g filter="url(#ifnC8Oe)"><path stroke="url(#iOrGicd)" class="v7en2lb3d"/></g><g filter="url(#iJTQ3vt)"><circle class="zelb7acvl"/></g><g filter="url(#inZcD0d)"><circle class="mv9vusbzb"/></g><g filter="url(#ituBZWb)"><circle transform="rotate(44.841 23.856 21.576)" class="ffrer35vo"/></g><path fill="url(#iNeSftY)" class="o46_q4b-v"/><path fill="url(#ifLfgUs)" class="o46_q4b-v"/><g filter="url(#ikNBbCL)"><path fill="url(#iH2oO6c)" class="xcc4ogbjc"/></g></g><defs><linearGradient id="iri0tkb" x1="9.547" x2="9.547" y1="21.551" y2="24.994" gradientUnits="userSpaceOnUse"><stop class="klygz_bbk"/><stop offset="1" class="g9sqibbhk"/><stop offset="1" class="wkoj-9b_c"/><stop offset="1" class="lg4v5ccoz"/></linearGradient><linearGradient id="iPOCpib" x1="3.625" x2="3.625" y1="13.566" y2="21.551" gradientUnits="userSpaceOnUse"><stop class="q9scrpbaq"/><stop offset="1" class="hx-qw4wbm"/></linearGradient><linearGradient id="i8GzTPt" x1="5.727" x2="5.727" y1="22.347" y2="17.222" gradientUnits="userSpaceOnUse"><stop class="xrv035b0t"/><stop offset="1" class="gz83bdccn"/></linearGradient><linearGradient id="i53VEmc" x1="2.406" x2="5.781" y1="17.56" y2="17.56" gradientUnits="userSpaceOnUse"><stop offset=".006" class="gps4qrbxp"/><stop offset=".37" class="dnw2t1sgj"/><stop offset="1" class="cwicf5bhb"/></linearGradient><linearGradient id="iC2tvPd" x1="21.266" x2="23.12" y1="22.816" y2="20.629" gradientUnits="userSpaceOnUse"><stop class="uhafftb5g"/><stop offset="1" class="jl87hdbxi"/></linearGradient><linearGradient id="ibInzae" x1="22.25" x2="23.609" y1="21.613" y2="20.222" gradientUnits="userSpaceOnUse"><stop class="yu-iu0qge"/><stop offset="1" class="ltdp0x8ky"/></linearGradient><linearGradient id="ifB5Nyd" x1="24.074" x2="24.074" y1="17.847" y2="15.426" gradientUnits="userSpaceOnUse"><stop class="j1ndf6x0v"/><stop offset="1" class="jl87hdbxi"/></linearGradient><linearGradient id="iqF4uMd" x1="24.539" x2="24.539" y1="18.707" y2="16.83" gradientUnits="userSpaceOnUse"><stop offset=".525" class="yu-iu0qge"/><stop offset="1" class="ltdp0x8ky"/></linearGradient><linearGradient id="irGYSSc" x1="24.219" x2="22.625" y1="13.676" y2="12.285" gradientUnits="userSpaceOnUse"><stop class="j1ndf6x0v"/><stop offset="1" class="jl87hdbxi"/></linearGradient><linearGradient id="iuOBVOd" x1="13.171" x2="12.19" y1="15.06" y2="15.06" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset=".855" class="co-foyhmg"/></linearGradient><linearGradient id="iweSVXd" x1="13.68" x2="13.68" y1="16.897" y2="15.808" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="idzw08d" x1="11.492" x2="12.216" y1="15.243" y2="15.243" gradientUnits="userSpaceOnUse"><stop class="kfeabacio"/><stop offset="1" class="c_lfom8in"/></linearGradient><linearGradient id="iRNfQMd" x1="10.031" x2="10.031" y1="21.888" y2="20.326" gradientUnits="userSpaceOnUse"><stop class="bldayib8v"/><stop offset="1" class="rh1ct20pt"/></linearGradient><linearGradient id="im6tpRv" x1="8.672" x2="10.578" y1="17.488" y2="20.472" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="iCF2t9b" x1="28.759" x2="28.759" y1="9.597" y2="27.16" gradientUnits="userSpaceOnUse"><stop class="sp6x0v1tw"/><stop offset="1" class="n1aq-5i_m"/></linearGradient><linearGradient id="is8jkKb" x1="23.945" x2="22.359" y1="12.152" y2="13.644" gradientUnits="userSpaceOnUse"><stop class="ebz8bhkkz"/><stop offset="1" class="xejel6bip"/></linearGradient><linearGradient id="ixGlJMb" x1="25.023" x2="23.438" y1="15.507" y2="17" gradientUnits="userSpaceOnUse"><stop class="ebz8bhkkz"/><stop offset="1" class="xejel6bip"/></linearGradient><linearGradient id="iOrGicd" x1="24.116" x2="21.939" y1="19.928" y2="19.868" gradientUnits="userSpaceOnUse"><stop class="ebz8bhkkz"/><stop offset="1" class="xejel6bip"/></linearGradient><linearGradient id="iNeSftY" x1="11.813" x2="11.813" y1="21.465" y2="21.793" gradientUnits="userSpaceOnUse"><stop class="zajgezbea"/><stop offset="1" class="y5hiv3btb"/></linearGradient><linearGradient id="ifLfgUs" x1="18.078" x2="14.875" y1="21.863" y2="21.863" gradientUnits="userSpaceOnUse"><stop class="dqdetrr3x"/><stop offset="1" class="za7okgbps"/></linearGradient><linearGradient id="iH2oO6c" x1="17.625" x2="16.549" y1="4.206" y2="5.524" gradientUnits="userSpaceOnUse"><stop class="bp9-03pgc"/><stop offset=".953" class="s4ac5qbbc"/></linearGradient><filter id="iHKl1ep" width="13.994" height="15.016" x="18.25" y="3.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation="1.5"/></filter><filter id="iMbLhhe" width="14.625" height="8.625" x="15.634" y="20.06" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".75"/></filter><filter id="iEMTOfb" width="4.247" height="4.247" x="21.029" y="18.546" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="i340RoR" width="4.855" height="2.797" x="22.02" y="15.653" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="i9agWfd" width="3.71" height="3.71" x="20.787" y="11.133" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="iOfOxse" width="3.602" height="5" x="10.563" y="12.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".5"/></filter><filter id="iY2KEdd" width="4.644" height="5.3" x="8.022" y="16.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="iZolOKc" width="2.018" height="19.063" x="27.75" y="8.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".375"/></filter><filter id="iPB73vc" width="2.761" height="2.741" x="21.772" y="11.383" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="iBcR0jP" width="3.031" height="1.25" x="23.188" y="15.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="ifnC8Oe" width="2.617" height="2.61" x="21.812" y="19.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="iJTQ3vt" width="1.683" height="1.683" x="23.156" y="11.04" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="inZcD0d" width="1.683" height="1.683" x="24.953" y="15.989" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="ituBZWb" width="1.683" height="1.683" x="23.015" y="20.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".25"/></filter><filter id="ikNBbCL" width="2.168" height="2.581" x="15.85" y="4.15" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3043" stdDeviation=".075"/></filter><radialGradient id="iA4m5id" cx="0" cy="0" r="1" gradientTransform="matrix(-2.57814 2.23436 -.8806 -1.0161 24.945 3.629)" gradientUnits="userSpaceOnUse"><stop class="x7n4m4bjv"/><stop offset="1" class="srpvqcbsk"/></radialGradient><radialGradient id="i3Hkb6M" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43752 6.625 -5.41222 -1.99131 7.367 7.363)" gradientUnits="userSpaceOnUse"><stop class="bp9-03pgc"/><stop offset=".953" class="s4ac5qbbc"/></radialGradient><radialGradient id="i0PR2Ic" cx="0" cy="0" r="1" gradientTransform="rotate(138.198 8.164 5.51)scale(3.45849 4.90823)" gradientUnits="userSpaceOnUse"><stop class="l7oc6lbok"/><stop offset="1" class="yqtvd-bwb"/></radialGradient><radialGradient id="inI9vIb" cx="0" cy="0" r="1" gradientTransform="matrix(17.18747 -6.5625 3.5865 9.39319 10.742 24.66)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="y1ockxb5w"/><stop offset="1" class="klygz_bbk"/></radialGradient><radialGradient id="ioLyAEc" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 3.3125 -9.6125 4.80624 9.133 19.455)" gradientUnits="userSpaceOnUse"><stop class="bofht_itb"/><stop offset="1" class="bk67amb-j"/></radialGradient><radialGradient id="itg9jkc" cx="0" cy="0" r="1" gradientTransform="matrix(-7.5625 -3.6875 3.70845 -7.60548 27.11 23.976)" gradientUnits="userSpaceOnUse"><stop class="ljzjjebqg"/><stop offset="1" class="h83-l8bax"/></radialGradient><radialGradient id="i4X8l2G" cx="0" cy="0" r="1" gradientTransform="rotate(-76.13 26.818 1.56)scale(5.21454 16.8117)" gradientUnits="userSpaceOnUse"><stop class="g578_nbmi"/><stop offset=".693" class="hbhklbcmn"/></radialGradient><radialGradient id="iUcPMVc" cx="0" cy="0" r="1" gradientTransform="matrix(7.21875 -6.875 2.86814 3.01155 18.563 9.097)" gradientUnits="userSpaceOnUse"><stop class="fz2fd_bfo"/><stop offset="1" class="aq3ai4bve"/></radialGradient><radialGradient id="ixqOaGF" cx="0" cy="0" r="1" gradientTransform="rotate(46.469 3.716 27.844)scale(2.58621 8.49082)" gradientUnits="userSpaceOnUse"><stop class="be1k8kyaa"/><stop offset="1" class="dlcssibfu"/></radialGradient><radialGradient id="ioJ6cvc" cx="0" cy="0" r="1" gradientTransform="matrix(1.78687 1.495 -8.43897 10.08652 21.219 19.42)" gradientUnits="userSpaceOnUse"><stop class="k4-5ejb7i"/><stop offset="1" class="xw5_6-1xo"/></radialGradient><radialGradient id="ig1RupT" cx="0" cy="0" r="1" gradientTransform="matrix(2.07007 0 0 5.44868 22.469 16.83)" gradientUnits="userSpaceOnUse"><stop class="k4-5ejb7i"/><stop offset="1" class="xw5_6-1xo"/></radialGradient><radialGradient id="iF2aybA" cx="0" cy="0" r="1" gradientTransform="rotate(-69.834 21.55 -8.81)scale(1.81295)" gradientUnits="userSpaceOnUse"><stop class="yu-iu0qge"/><stop offset="1" class="ltdp0x8ky"/></radialGradient><radialGradient id="is94T2d" cx="0" cy="0" r="1" gradientTransform="rotate(156.658 3.942 10.612)scale(4.10129 5.31031)" gradientUnits="userSpaceOnUse"><stop offset=".831" class="uabtk-bkr"/><stop offset="1" class="u20oaq2fs"/></radialGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:boar" /></template>
<style>
.aq3ai4bve {
  stop-color: var(--svg-color--ff768a, #FF768A);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.be1k8kyaa {
  stop-color: var(--svg-color--ff7287, #FF7287);
  stop-opacity: 0;
}

.bg8prvb4b {
  d: path("M7.856 17.042c-.317 1.924.263 3.86.855 4.518h5.125c-2.676-1.65-3.976-3.07-4.598-4.445c-.244-.766-1.191-.762-1.382-.073");
}

.bk67amb-j {
  stop-color: var(--svg-color--7a4f51, #7A4F51);
  stop-opacity: 0;
}

.bldayib8v {
  stop-color: var(--svg-color--e0ccf1, #E0CCF1);
}

.bofht_itb {
  stop-color: var(--svg-color--7a4f51, #7A4F51);
}

.bp9-03pgc {
  stop-color: var(--svg-color--eec8c1, #EEC8C1);
}

.bs_5n4vkk {
  d: path("M5.727 17.09c0-2.29-2.532-3.524-3.383-3.524a.79.79 0 0 0-.82.802v6.464c0 .403.437.719.843.719c1.594 0 3.36-2.235 3.36-4.461");
}

.c_lfom8in {
  stop-color: var(--svg-color--574d50, #574D50);
  stop-opacity: 0;
}

.co-foyhmg {
  stop-color: var(--svg-color--31232c, #31232C);
}

.cwicf5bhb {
  stop-color: var(--svg-color--312125, #312125);
}

.d7c-wnbhm {
  fill: var(--svg-color--7a4045, #7A4045);
  d: path("M25.477 17.95h-2.058a.905.905 0 0 1-.899-.899c0-.491.407-.898.899-.898h2.058c.491 0 .898.407.898.898a.905.905 0 0 1-.898.899");
}

.dlcssibfu {
  stop-color: var(--svg-color--ff677e, #FF677E);
}

.dnw2t1sgj {
  stop-color: var(--svg-color--3d2f37, #3D2F37);
}

.dqdetrr3x {
  stop-color: var(--svg-color--9a635e, #9A635E);
}

.e3xgskbhi {
  d: path("M29.617 21.56H2.282a.94.94 0 0 1-.665-.9v-6.12c0-.52.42-.94.94-.94c2.53 0 4.9-1.27 6.3-3.39l1.14-1.71a8.7 8.7 0 0 1 7.26-3.9c.21 0 .4-.1.52-.27a6.17 6.17 0 0 1 5.12-2.73h1.47c1.09 0 1.84 1.09 1.46 2.1c0 0-.63 1.69-.98 2.61c-.06.16.01.34.17.4l3.82 1.57c.47.19.78.65.78 1.16z");
}

.ebz8bhkkz {
  stop-color: var(--svg-color--c89b8b, #C89B8B);
}

.f1y5xoijx {
  fill: var(--svg-color--7a4045, #7A4045);
  d: path("m23.78 12.912l-1.215 1.214c-.29.29-.77.29-1.06 0a.755.755 0 0 1 0-1.06l1.215-1.215c.29-.29.77-.29 1.06 0s.29.77 0 1.06");
}

.ffrer35vo {
  cx: 23.856px;
  cy: 21.576px;
  r: 0.341px;
  fill: var(--svg-color--c89b8b, #C89B8B);
}

.ft5dv1b6b {
  fill: none;
}

.fz2fd_bfo {
  stop-color: var(--svg-color--ffa9c7, #FFA9C7);
}

.g578_nbmi {
  stop-color: var(--svg-color--863969, #863969);
}

.g9sqibbhk {
  stop-color: var(--svg-color--84475a, #84475A);
}

.gd4uyvbey {
  d: path("m28.775 8.256l-3.82-1.57a.306.306 0 0 1-.17-.4c.35-.92.785-2.126.785-2.126c.38-1.01-.37-2.1-1.46-2.1h-1.47c-2.09 0-3.795.566-4.925 2.246c-.12.17-.31.27-.52.27c-2.92 0-5.65 1.46-7.26 3.9l-1.14 1.71a7.55 7.55 0 0 1-6.3 3.39c-.52 0-.94.42-.94.94v6.12c0 .52.42.94.94.94h3.06c1.25 1.87 3.35 3 5.61 3h5.36c1.34 0 2.66.29 3.88.84l7.83 3.56a.935.935 0 0 0 1.32-.86v-18.7c0-.51-.31-.97-.78-1.16");
}

.gps4qrbxp {
  stop-color: var(--svg-color--26141b, #26141B);
}

.gz83bdccn {
  stop-color: var(--svg-color--e585b0, #E585B0);
  stop-opacity: 0;
}

.h83-l8bax {
  stop-color: var(--svg-color--8d515b, #8D515B);
  stop-opacity: 0;
}

.hbhklbcmn {
  stop-color: var(--svg-color--863969, #863969);
  stop-opacity: 0;
}

.hx-qw4wbm {
  stop-color: var(--svg-color--f791b1, #F791B1);
}

.ibtrv6u-z {
  d: path("M28.5 9.597h.518V27.16H28.5z");
}

.j1ndf6x0v {
  stop-color: var(--svg-color--a66d5b, #A66D5B);
}

.jl87hdbxi {
  stop-color: var(--svg-color--a56558, #A56558);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jzgc8si5q {
  d: path("m21.865 20.83l1.34 1.34c.32.32.85.32 1.17 0s.32-.85 0-1.17l-1.34-1.34a.833.833 0 0 0-1.17 0c-.32.32-.32.84 0 1.17");
}

.k4-5ejb7i {
  stop-color: var(--svg-color--8b5646, #8B5646);
}

.kfeabacio {
  stop-color: var(--svg-color--574d50, #574D50);
}

.klygz_bbk {
  stop-color: var(--svg-color--80376b, #80376B);
  stop-opacity: 0;
}

.l7oc6lbok {
  stop-color: var(--svg-color--745953, #745953);
}

.lg4v5ccoz {
  stop-color: var(--svg-color--80376b, #80376B);
}

.ljzjjebqg {
  stop-color: var(--svg-color--8d515b, #8D515B);
}

.ltdp0x8ky {
  stop-color: var(--svg-color--9d5960, #9D5960);
  stop-opacity: 0;
}

.mconsebpi {
  d: path("M5.547 21.55c1.25 1.87 3.35 3 5.61 3h5.36c1.34 0 2.66.29 3.88.84l7.83 3.56a.935.935 0 0 0 1.32-.86v-6.54z");
}

.mf_46vu0u {
  fill: var(--svg-color--77453f, #77453F);
  d: path("m23.245 22.033l-1.456-1.455a.905.905 0 0 1 0-1.271a.905.905 0 0 1 1.271 0l1.455 1.455a.905.905 0 0 1 0 1.27a.905.905 0 0 1-1.27 0");
}

.mv9vusbzb {
  cx: 25.794px;
  cy: 16.83px;
  r: 0.341px;
  fill: var(--svg-color--c89b8b, #C89B8B);
}

.n1aq-5i_m {
  stop-color: var(--svg-color--b98a80, #B98A80);
  stop-opacity: 0;
}

.o46_q4b-v {
  d: path("M18.078 21.56v.381H5.821a7 7 0 0 1-.274-.381z");
}

.pcwpw8gsa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M8.672 17.191c.208.73 1.169 2.55 3.344 4");
}

.q0_flrbub {
  d: path("M11.43 6.754c2.023-.907 3.317-1.252 3.348-1.275c.05-.038 2.417-.163 2.972-1.224l-.035.05c-.12.17-.31.27-.52.27c-2.148 0-4.193.79-5.765 2.179");
}

.q9scrpbaq {
  stop-color: var(--svg-color--ffa8b1, #FFA8B1);
}

.rh1ct20pt {
  stop-color: var(--svg-color--e0ccf1, #E0CCF1);
  stop-opacity: 0;
}

.rxr7ftbpw {
  d: path("m28.697 8.26l-3.82-1.57a.306.306 0 0 1-.17-.4c.35-.92.785-2.126.785-2.126c.38-1.01-.37-2.1-1.46-2.1h-1.47c-2.09 0-3.795.566-4.925 2.246c-.12.17-.31.27-.52.27c-2.92 0-5.65 1.46-7.26 3.9l-1.14 1.71a7.55 7.55 0 0 1-6.3 3.39c-.52 0-.94.42-.94.94v6.12c0 .52.42.94.94.94h3.06c1.25 1.87 3.35 3 5.61 3h5.36c1.34 0 2.66.29 3.88.84l7.83 3.56a.935.935 0 0 0 1.32-.86V9.42c0-.51-.31-.97-.78-1.16");
}

.s4ac5qbbc {
  stop-color: var(--svg-color--a58a85, #A58A85);
  stop-opacity: 0;
}

.sp6x0v1tw {
  stop-color: var(--svg-color--b98a80, #B98A80);
}

.srpvqcbsk {
  stop-color: var(--svg-color--b68a7f, #B68A7F);
  stop-opacity: 0;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.tczwdqbbd {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m22.36 13.535l1.585-1.563");
}

.tlve2kzem {
  fill: var(--svg-color--99625f, #99625F);
  d: path("M28.759 27.185L17.134 21.56h11.625z");
}

.tly2-yyal {
  d: path("M3.125 19.56c-.28 0-.5-.22-.5-.5v-3c0-.28.22-.5.5-.5s.5.22.5.5v3c0 .28-.22.5-.5.5");
}

.u20oaq2fs {
  stop-color: var(--svg-color--d2cad7, #D2CAD7);
}

.uabtk-bkr {
  stop-color: var(--svg-color--d7cedc, #D7CEDC);
  stop-opacity: 0;
}

.uhafftb5g {
  stop-color: var(--svg-color--9e6d59, #9E6D59);
}

.v7en2lb3d {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m22.4 19.759l1.44 1.432");
}

.vc_j-ab_f {
  stroke: var(--svg-color--b98a80, #B98A80);
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
  d: path("M22.5 6.472c0 3.5 2.625 6.75 6.406 7.813");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vv04up0mj {
  d: path("M25.625 17.66h-1.9c-.46 0-.83-.37-.83-.83s.37-.83.83-.83h1.9c.46 0 .83.37.83.83s-.37.83-.83.83");
}

.wkoj-9b_c {
  stop-color: var(--svg-color--7a3b4f, #7A3B4F);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x57j-7b1f {
  d: path("m24.224 5.433l.36-1.117c.11-.399 0-.711-.36-.711l-1.233-.04c-2.063 0-3.773 1.413-4.453 3.243l-.743 1.875c-.15.484-.085.934.54.914c2.859-.094 4.867-1.57 5.889-4.164");
}

.x7n4m4bjv {
  stop-color: var(--svg-color--b68a7f, #B68A7F);
}

.xcc4ogbjc {
  d: path("m16.68 6.581l1.188-2.28c-.274.526-1.157.808-1.868.976z");
}

.xdmz11brs {
  fill: var(--svg-color--875354, #875354);
  d: path("M12.363 16.56c-.44 0-.8-.337-.8-.75v-1.5c0-.412.36-.75.8-.75s.801.338.801.75v1.5c0 .412-.36.75-.8.75");
}

.xejel6bip {
  stop-color: var(--svg-color--c89b8b, #C89B8B);
  stop-opacity: 0;
}

.xfpaktsqo {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.688 16.597h2.03");
}

.xrv035b0t {
  stop-color: var(--svg-color--e585b0, #E585B0);
}

.xu_kaabou {
  fill: var(--svg-color--9a645b, #9A645B);
  d: path("m28.775 8.256l-3.82-1.57a.306.306 0 0 1-.17-.4c.35-.92.785-2.126.785-2.126c.38-1.01-.37-2.1-1.46-2.1h-1.47c-2.09 0-3.795.566-4.925 2.246c-.12.17-.31.27-.52.27c-2.92 0-5.65 1.46-7.26 3.9l-1.14 1.71a7.55 7.55 0 0 1-6.3 3.39c-.52 0-.94.42-.94.94v6.12c0 .52.42.94.94.94h3.06c1.25 1.87 3.35 3 5.61 3h5.36c1.34 0 2.66.29 3.88.84l7.83 3.56a.935.935 0 0 0 1.32-.86v-18.7c0-.51-.31-.97-.78-1.16");
}

.xw5_6-1xo {
  stop-color: var(--svg-color--8b5646, #8B5646);
  stop-opacity: 0;
}

.y1ockxb5w {
  stop-color: var(--svg-color--722f5f, #722F5F);
}

.y5hiv3btb {
  stop-color: var(--svg-color--561f1a, #561F1A);
  stop-opacity: 0;
}

.yqtvd-bwb {
  stop-color: var(--svg-color--876962, #876962);
  stop-opacity: 0;
}

.ysza622gu {
  d: path("M12.629 16.56c-.44 0-.8-.337-.8-.75v-1.5c0-.412.36-.75.8-.75s.8.338.8.75v1.5c0 .412-.36.75-.8.75");
}

.yu-iu0qge {
  stop-color: var(--svg-color--9d5960, #9D5960);
}

.za7okgbps {
  stop-color: var(--svg-color--9a635e, #9A635E);
  stop-opacity: 0;
}

.zajgezbea {
  stop-color: var(--svg-color--561f1a, #561F1A);
}

.zdv_i-bwc {
  fill: var(--svg-color--eee0f9, #EEE0F9);
  d: path("M7.856 17.042c-.317 1.924.263 3.86.855 4.518h5.125c-2.676-1.65-3.976-3.07-4.598-4.445c-.244-.766-1.191-.762-1.382-.073");
}

.zelb7acvl {
  cx: 23.998px;
  cy: 11.881px;
  r: 0.341px;
  fill: var(--svg-color--c89b8b, #C89B8B);
}

.zuoybg3sf {
  d: path("m24.385 12.67l-1.34 1.34c-.32.32-.85.32-1.17 0a.833.833 0 0 1 0-1.17l1.34-1.34c.32-.32.85-.32 1.17 0s.32.85 0 1.17");
}

</style>
