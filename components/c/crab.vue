<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="oy5zpibej"/><path fill="url(#iWIGiMb)" class="n-x53sa9v"/><path fill="url(#iL6FxTd)" class="q_gqhe9iv"/><path fill="url(#iZtONDb)" class="m0ro3i4fu"/><path fill="url(#iXBJlgG)" class="rve4g8b0f"/><path fill="url(#iML5XDc)" class="fjkh1j9zv"/><path fill="url(#iOBi1sc)" class="gcwg0cbow"/><path fill="url(#iMc96cb)" class="l7-2u8b-r"/><path fill="url(#iSwaohb)" class="f5cmlrikt"/><path stroke="url(#iAZmGrd)" class="j8llrhbkr"/><path class="n98idlbgo"/><path stroke="url(#ibxLhJc)" class="zov1arbng"/><path stroke="url(#i1AIoAM)" class="rvdkuw25u"/><path fill="url(#i7oPa7d)" class="w_renqbra"/><path fill="url(#iE6WhHe)" class="jygqdef5j"/><path fill="url(#isS76xd)" class="jygqdef5j"/><path fill="url(#iWzLs8b)" class="jygqdef5j"/><path fill="url(#ixF2aKd)" class="tt7ka7bcu"/><path fill="url(#iMrBrud)" class="tt7ka7bcu"/><path stroke="url(#iv4cE2d)" class="ic8iny-mg"/><path stroke="url(#ifSaX9c)" class="ic8iny-mg"/><path stroke="url(#iq6cd5b)" class="ic8iny-mg"/><path fill="url(#ii0z9se)" class="ghisg_rvt"/><path fill="url(#idVU17g)" class="ghisg_rvt"/><path fill="url(#iQnR3Oc)" class="lj_wzm5vq"/><path fill="url(#ihiGwvc)" class="xsvfp_f3u"/><path fill="url(#i1d9lCe)" class="xsvfp_f3u"/><g filter="url(#ichz8fb)"><path fill="url(#iqFGmbb)" class="nz9lihbmq"/></g><g filter="url(#iqxR6Zb)"><path fill="url(#i5bSpDc)" class="z0hrhzbme"/></g><g filter="url(#icc4usd)"><path fill="url(#icn286y)" class="l8ncnsbub"/></g><path class="s4tq2tbyz"/><path fill="url(#iTxT1Cc)" class="wz7_3bkmz"/><path fill="url(#iqqLNQe)" class="wz7_3bkmz"/><path fill="url(#iQJmmde)" class="wz7_3bkmz"/><path class="o2t45ac7v"/><path fill="url(#iQGQNCc)" class="a3vaj_pje"/><path fill="url(#ioJDvxe)" class="a3vaj_pje"/><path fill="url(#iBAhpyb)" class="a3vaj_pje"/><g filter="url(#iH8jkYb)"><path stroke="url(#isGX7EX)" class="cl2cunbvf"/></g><g filter="url(#iGZEKHS)"><path stroke="url(#iBvI6Bb)" class="l_8jtu3ur"/></g><g filter="url(#iQU5o7c)"><path fill="url(#i286K4b)" class="ui71nvg6n"/></g><g filter="url(#iDCZ53b)"><path fill="url(#iQxTL3c)" class="afvv-cplu"/></g><g filter="url(#iWt6a7D)"><path fill="url(#iJ4dPie)" class="iankmt-7f"/></g><g filter="url(#iTZhuSb)"><path fill="url(#io1SFse)" class="c3bcnpnjy"/></g><defs><radialGradient id="iWIGiMb" cx="0" cy="0" r="1" gradientTransform="matrix(.125 3.34375 -7.98716 .2986 28.624 21.906)" gradientUnits="userSpaceOnUse"><stop offset=".306" class="ptp8dmbsw"/><stop offset=".806" class="m3karnq7v"/></radialGradient><radialGradient id="iL6FxTd" cx="0" cy="0" r="1" gradientTransform="matrix(2.75 2.4375 -8.12127 9.16246 28.75 15.875)" gradientUnits="userSpaceOnUse"><stop offset=".129" class="s7k3i1btx"/><stop offset="1" class="m3karnq7v"/></radialGradient><radialGradient id="iZtONDb" cx="0" cy="0" r="1" gradientTransform="matrix(3.25 5.25 -3.61923 2.24048 24 26.625)" gradientUnits="userSpaceOnUse"><stop offset=".388" class="ptp8dmbsw"/><stop offset=".806" class="m3karnq7v"/></radialGradient><radialGradient id="iXBJlgG" cx="0" cy="0" r="1" gradientTransform="matrix(-2.37502 5.4375 -3.00705 -1.31343 19.063 28.875)" gradientUnits="userSpaceOnUse"><stop offset=".497" class="ptp8dmbsw"/><stop offset="1" class="m3karnq7v"/></radialGradient><radialGradient id="iML5XDc" cx="0" cy="0" r="1" gradientTransform="rotate(27.793 -41.607 19.677)scale(8.88425 4.99007)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="ptp8dmbsw"/><stop offset=".593" class="m3karnq7v"/></radialGradient><radialGradient id="iOBi1sc" cx="0" cy="0" r="1" gradientTransform="rotate(56.844 -13.427 12.481)scale(10.959 6.83273)" gradientUnits="userSpaceOnUse"><stop offset=".191" class="ptp8dmbsw"/><stop offset=".593" class="m3karnq7v"/></radialGradient><radialGradient id="iMc96cb" cx="0" cy="0" r="1" gradientTransform="matrix(7.0625 4.875 -3.2219 4.66763 6.313 26.125)" gradientUnits="userSpaceOnUse"><stop offset=".276" class="ptp8dmbsw"/><stop offset=".687" class="m3karnq7v"/></radialGradient><radialGradient id="iSwaohb" cx="0" cy="0" r="1" gradientTransform="matrix(3.28589 5.875 -3.249 1.81716 10.652 28.625)" gradientUnits="userSpaceOnUse"><stop offset=".497" class="ptp8dmbsw"/><stop offset=".803" class="m3karnq7v"/></radialGradient><radialGradient id="iAZmGrd" cx="0" cy="0" r="1" gradientTransform="rotate(81.916 -3.64 11.77)scale(3.59826 2.77085)" gradientUnits="userSpaceOnUse"><stop offset=".303" class="wzh_6eg-b"/><stop offset=".45" class="m3w43hb5p"/><stop offset=".69" class="onpxecnsg"/><stop offset="1" class="eyonxvbek"/></radialGradient><radialGradient id="i7oPa7d" cx="0" cy="0" r="1" gradientTransform="matrix(1.25147 -.8838 1.13462 1.60662 13.404 8.29)" gradientUnits="userSpaceOnUse"><stop class="mvvuk09qe"/><stop offset="1" class="k1evavb6p"/></radialGradient><radialGradient id="iE6WhHe" cx="0" cy="0" r="1" gradientTransform="rotate(130.727 1.043 7.668)scale(1.29318)" gradientUnits="userSpaceOnUse"><stop class="a3hn5r2oa"/><stop offset=".538" class="op29lb3_e"/></radialGradient><radialGradient id="isS76xd" cx="0" cy="0" r="1" gradientTransform="rotate(97.595 -1.218 8.926)scale(.70935 1.04505)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="g6vbqcbdj"/><stop offset="1" class="vric1mb3o"/></radialGradient><radialGradient id="iWzLs8b" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 .5106 -.74732 1.00623 5.969 11.88)" gradientUnits="userSpaceOnUse"><stop class="gwhaq42rp"/><stop offset="1" class="bh61-9bmy"/></radialGradient><radialGradient id="ixF2aKd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.43749 -3.12502 4.17534 -4.59282 11.563 10.063)" gradientUnits="userSpaceOnUse"><stop class="d-kyhyb6q"/><stop offset=".47" class="ofkxeblxx"/><stop offset=".824" class="vt6_nubcr"/><stop offset="1" class="i3fkxf2eg"/></radialGradient><radialGradient id="iMrBrud" cx="0" cy="0" r="1" gradientTransform="matrix(-8.31247 7.31246 -2.93977 -3.3418 12.625 5.688)" gradientUnits="userSpaceOnUse"><stop offset=".707" class="txvr8eipx"/><stop offset=".834" class="eocfbzb4z"/></radialGradient><radialGradient id="iv4cE2d" cx="0" cy="0" r="1" gradientTransform="matrix(2.69531 1.64844 -2.6318 4.30317 22.36 13.922)" gradientUnits="userSpaceOnUse"><stop offset=".392" class="zrwonab6q"/><stop offset=".503" class="oz2kptbvf"/><stop offset=".724" class="zyeypfbry"/><stop offset="1" class="oombh1b1l"/></radialGradient><radialGradient id="ifSaX9c" cx="0" cy="0" r="1" gradientTransform="rotate(115.017 8.272 14.635)scale(.51728)" gradientUnits="userSpaceOnUse"><stop class="i9c1akdkr"/><stop offset="1" class="kgcv75bov"/></radialGradient><radialGradient id="iq6cd5b" cx="0" cy="0" r="1" gradientTransform="rotate(60.581 1.466 27.507)scale(.66372 .74404)" gradientUnits="userSpaceOnUse"><stop class="aa0-w6bke"/><stop offset="1" class="c1z0qzb-l"/></radialGradient><radialGradient id="ii0z9se" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.1875 -3.04132 0 18.145 5.938)" gradientUnits="userSpaceOnUse"><stop class="kojl241im"/><stop offset="1" class="ldolr3bst"/></radialGradient><radialGradient id="iQnR3Oc" cx="0" cy="0" r="1" gradientTransform="matrix(1.25147 -.8838 1.13462 1.60662 17.844 8.29)" gradientUnits="userSpaceOnUse"><stop class="mvvuk09qe"/><stop offset="1" class="k1evavb6p"/></radialGradient><radialGradient id="ihiGwvc" cx="0" cy="0" r="1" gradientTransform="rotate(130.727 9.823 11.694)scale(1.29318)" gradientUnits="userSpaceOnUse"><stop class="sypvssbqq"/><stop offset=".538" class="c1s-0nbic"/></radialGradient><radialGradient id="i1d9lCe" cx="0" cy="0" r="1" gradientTransform="matrix(.24219 .38281 -1.0206 .6457 24.851 11.25)" gradientUnits="userSpaceOnUse"><stop offset=".408" class="undnrubxu"/><stop offset="1" class="vric1mb3o"/></radialGradient><radialGradient id="iqFGmbb" cx="0" cy="0" r="1" gradientTransform="matrix(.95382 -4.59535 3.03839 .63065 20.062 29.163)" gradientUnits="userSpaceOnUse"><stop class="t07jf7kdj"/><stop offset="1" class="h8yegupsw"/></radialGradient><radialGradient id="i5bSpDc" cx="0" cy="0" r="1" gradientTransform="matrix(3.46504 -3.1655 2.093 2.29105 6.286 26.77)" gradientUnits="userSpaceOnUse"><stop class="s97one1oy"/><stop offset="1" class="h8yegupsw"/></radialGradient><radialGradient id="icn286y" cx="0" cy="0" r="1" gradientTransform="matrix(-.16169 -3.34788 2.21358 -.1069 12.845 29.535)" gradientUnits="userSpaceOnUse"><stop class="t07jf7kdj"/><stop offset="1" class="h8yegupsw"/></radialGradient><radialGradient id="iTxT1Cc" cx="0" cy="0" r="1" gradientTransform="rotate(-41.532 25.6 -18.79)scale(7.06971)" gradientUnits="userSpaceOnUse"><stop offset=".456" class="sij0lqbjd"/><stop offset="1" class="w0rqqac4v"/></radialGradient><radialGradient id="iqqLNQe" cx="0" cy="0" r="1" gradientTransform="rotate(90 7.312 16.5)scale(3.9375)" gradientUnits="userSpaceOnUse"><stop class="iqug87bzo"/><stop offset="1" class="nscc955sb"/></radialGradient><radialGradient id="iQJmmde" cx="0" cy="0" r="1" gradientTransform="matrix(5.375 -6.375 8.78925 7.41055 22.75 7.938)" gradientUnits="userSpaceOnUse"><stop offset=".323" class="tpvcr5bus"/><stop offset=".451" class="t6dtxl50o"/></radialGradient><radialGradient id="iQGQNCc" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.75 -27.2695 0 23.875 16.5)" gradientUnits="userSpaceOnUse"><stop class="d9dv6n_0o"/><stop offset="1" class="c1o1tg9lz"/></radialGradient><radialGradient id="ioJDvxe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.44979 9.625 -14.93819 -2.2501 17.375 21.5)" gradientUnits="userSpaceOnUse"><stop offset=".811" class="s189hlbno"/><stop offset=".9" class="ssla29buu"/></radialGradient><radialGradient id="iBAhpyb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.50002 11.06492 -12.05709 -13.62087 20.688 20.06)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="z3daj8abh"/><stop offset=".778" class="d494whloj"/></radialGradient><radialGradient id="isGX7EX" cx="0" cy="0" r="1" gradientTransform="matrix(.09229 3.82813 -.35838 .00864 19.095 5.813)" gradientUnits="userSpaceOnUse"><stop offset=".217" class="pbwjsnb0x"/><stop offset="1" class="u3ub0_o0s"/></radialGradient><radialGradient id="iBvI6Bb" cx="0" cy="0" r="1" gradientTransform="matrix(-.47397 5.9375 -.55585 -.04437 12.755 5.813)" gradientUnits="userSpaceOnUse"><stop offset=".234" class="pbwjsnb0x"/><stop offset="1" class="u3ub0_o0s"/></radialGradient><radialGradient id="i286K4b" cx="0" cy="0" r="1" gradientTransform="rotate(112.839 9.689 17.058)scale(3.25386 2.15142)" gradientUnits="userSpaceOnUse"><stop class="t07jf7kdj"/><stop offset=".67" class="h8yegupsw"/></radialGradient><radialGradient id="iQxTL3c" cx="0" cy="0" r="1" gradientTransform="matrix(5.02277 4.74016 -3.13414 3.321 3.227 14.947)" gradientUnits="userSpaceOnUse"><stop class="t07jf7kdj"/><stop offset=".67" class="h8yegupsw"/></radialGradient><radialGradient id="iJ4dPie" cx="0" cy="0" r="1" gradientTransform="matrix(-3.13319 .87793 -.58048 -2.07163 29.44 21.143)" gradientUnits="userSpaceOnUse"><stop class="t07jf7kdj"/><stop offset=".67" class="h8yegupsw"/></radialGradient><radialGradient id="io1SFse" cx="0" cy="0" r="1" gradientTransform="rotate(-129.683 19.2 7.072)scale(4.69329 3.10315)" gradientUnits="userSpaceOnUse"><stop class="t07jf7kdj"/><stop offset="1" class="h8yegupsw"/></radialGradient><filter id="ichz8fb" width="1.815" height="5.281" x="19.5" y="24.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="iqxR6Zb" width="4.167" height="4.058" x="6.224" y="23.457" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="icc4usd" width="1.431" height="4.875" x="11.694" y="24.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="iH8jkYb" width="1.031" height="4.305" x="18.72" y="4.852" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="iGZEKHS" width="2.022" height="5.659" x="11.108" y="4.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="iQU5o7c" width="2.844" height="3.991" x="26.528" y="13.964" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="iDCZ53b" width="3.988" height="3.913" x="3.043" y="14.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="iWt6a7D" width="4.583" height="1.299" x="25.388" y="20.328" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><filter id="iTZhuSb" width="3.386" height="4.109" x="22.815" y="22.937" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_31679" stdDeviation=".125"/></filter><linearGradient id="ibxLhJc" x1="12.922" x2="14.125" y1="13" y2="13" gradientUnits="userSpaceOnUse"><stop class="p0etxehku"/><stop offset=".271" class="smhq_hewq"/><stop offset=".668" class="jm8654uxq"/><stop offset="1" class="byor_q_mm"/></linearGradient><linearGradient id="i1AIoAM" x1="17.891" x2="19.094" y1="13" y2="13" gradientUnits="userSpaceOnUse"><stop class="p0etxehku"/><stop offset=".271" class="smhq_hewq"/><stop offset=".668" class="jm8654uxq"/><stop offset="1" class="byor_q_mm"/></linearGradient><linearGradient id="idVU17g" x1="19.25" x2="18.328" y1="5.74" y2="5.74" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ky8g8ku3f"/><stop offset=".949" class="uy7ti0b4p"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crab" /></template>
<style>
.a3hn5r2oa {
  stop-color: var(--svg-color--f24576, #F24576);
}

.a3vaj_pje {
  d: path("M24.725 18.33a8.8 8.8 0 0 1-17.6 0c0-4.86 3.94-5.34 8.8-5.34s8.8.47 8.8 5.34");
}

.aa0-w6bke {
  stop-color: var(--svg-color--f30e47, #F30E47);
}

.afvv-cplu {
  d: path("M4.14 16.016c.44.555 2.641 1.78 2.641 1.78c-.287-.3-1.422-1.386-2.093-2.046c-.574-.564-1.128-1.457-1.295-1.358c-.354.208.309 1.068.748 1.624");
}

.bh61-9bmy {
  stop-color: var(--svg-color--ff8c92, #FF8C92);
  stop-opacity: 0;
}

.byor_q_mm {
  stop-color: var(--svg-color--553e43, #553E43);
}

.c1o1tg9lz {
  stop-color: var(--svg-color--ff3897, #FF3897);
  stop-opacity: 0;
}

.c1s-0nbic {
  stop-color: var(--svg-color--f22362, #F22362);
}

.c1z0qzb-l {
  stop-color: var(--svg-color--f5134b, #F5134B);
  stop-opacity: 0;
}

.c3bcnpnjy {
  d: path("M25.055 24.62c-.482-.656-1.99-1.433-1.99-1.433s1.237 1.087 1.708 1.907c.421.733.89 1.774 1.068 1.698c.378-.161-.304-1.514-.786-2.171");
}

.cl2cunbvf {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.095 5.102v2.18c0 .312.085 1.234.303 1.554");
}

.d-kyhyb6q {
  stop-color: var(--svg-color--ff31ad, #FF31AD);
}

.d494whloj {
  stop-color: var(--svg-color--ff739e, #FF739E);
}

.d9dv6n_0o {
  stop-color: var(--svg-color--ff69ac, #FF69AC);
}

.eocfbzb4z {
  stop-color: var(--svg-color--ff22b6, #FF22B6);
}

.eyonxvbek {
  stop-color: var(--svg-color--f67c7d, #F67C7D);
}

.f5cmlrikt {
  d: path("M13.345 23.18a.695.695 0 0 0-1.19-.51a5.22 5.22 0 0 0-1.5 3.47c-.05 1.36.42 2.61 1.24 3.57c.41.48 1.2.22 1.22-.42z");
}

.fjkh1j9zv {
  d: path("M8.745 20.39c.63 0 .92.77.46 1.2a5.156 5.156 0 0 1-6.98 0c-.46-.43-.17-1.2.46-1.2z");
}

.ft5dv1b6b {
  fill: none;
}

.g6vbqcbdj {
  stop-color: var(--svg-color--e60a44, #E60A44);
}

.gcwg0cbow {
  d: path("M8.015 18.56c.45.45.11 1.2-.52 1.17a5.13 5.13 0 0 1-3.43-1.51a5.13 5.13 0 0 1-1.51-3.43c-.03-.63.72-.97 1.17-.53z");
}

.ghisg_rvt {
  d: path("M18.675 6.48h.42V5h-1.9c0 .82.66 1.48 1.48 1.48");
}

.gwhaq42rp {
  stop-color: var(--svg-color--ff8990, #FF8990);
}

.h8yegupsw {
  stop-color: var(--svg-color--ff67c0, #FF67C0);
  stop-opacity: 0;
}

.i3fkxf2eg {
  stop-color: var(--svg-color--ff7f8e, #FF7F8E);
}

.i9c1akdkr {
  stop-color: var(--svg-color--ff6c7b, #FF6C7B);
}

.iankmt-7f {
  d: path("M28.389 21.362c-.703.09-2.75-.252-2.75-.252c.415-.015 1.472-.04 2.408-.178c.837-.122 1.613-.489 1.664-.302c.107.397-.62.643-1.322.732");
}

.ic8iny-mg {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-735px, 1.735px);
  d: path("M21.925 16.24a2.78 2.78 0 0 0 2.78-2.78");
}

.iqug87bzo {
  stop-color: var(--svg-color--ff6d8d, #FF6D8D);
}

.j8llrhbkr {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--1-735px, 1.735px);
  d: path("M9.915 16.24a2.78 2.78 0 0 1-2.78-2.78");
}

.jm8654uxq {
  stop-color: var(--svg-color--5a434c, #5A434C);
}

.jygqdef5j {
  d: path("M7.145 12.86a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.k1evavb6p {
  stop-color: var(--svg-color--f5166d, #F5166D);
}

.kgcv75bov {
  stop-color: var(--svg-color--ff6d7a, #FF6D7A);
  stop-opacity: 0;
}

.kojl241im {
  stop-color: var(--svg-color--fe1f9c, #FE1F9C);
}

.ky8g8ku3f {
  stop-color: var(--svg-color--f61a71, #F61A71);
}

.l_8jtu3ur {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.755 5.219V7.28c0 .86-.411 2.25-1.318 3");
}

.l7-2u8b-r {
  d: path("M11.305 23.58c.46-.43.15-1.19-.48-1.19c-1.25.01-2.5.47-3.48 1.38c-.99.92-1.53 2.13-1.63 3.38c-.05.63.69.99 1.15.57z");
}

.l8ncnsbub {
  d: path("M11.949 27.146c.078-1.535.582-2.052.582-2.052s.15 2.618.344 4.375c0 0-1.005-.79-.926-2.323");
}

.ldolr3bst {
  stop-color: var(--svg-color--ff4481, #FF4481);
}

.lj_wzm5vq {
  d: path("M18.675 6.81h.42v1.48h-1.9c0-.82.66-1.48 1.48-1.48");
}

.m0ro3i4fu {
  d: path("M20.605 23.55c-.47-.43-.15-1.2.48-1.2c1.26.01 2.52.47 3.51 1.4s1.55 2.15 1.65 3.4c.05.63-.7 1-1.16.57z");
}

.m3karnq7v {
  stop-color: var(--svg-color--f01147, #F01147);
}

.m3w43hb5p {
  stop-color: var(--svg-color--fe5d79, #FE5D79);
}

.mvvuk09qe {
  stop-color: var(--svg-color--ff1aaf, #FF1AAF);
}

.n-x53sa9v {
  d: path("M23.195 20.32c-.64 0-.93.78-.46 1.21a5.21 5.21 0 0 0 7.04 0c.47-.43.17-1.21-.46-1.21z");
}

.n98idlbgo {
  fill: var(--svg-color--ff3490, #FF3490);
  d: path("M13.175 6.48h-.42V5h1.9c0 .82-.66 1.48-1.48 1.48");
}

.nscc955sb {
  stop-color: var(--svg-color--ff6c8c, #FF6C8C);
  stop-opacity: 0;
}

.nz9lihbmq {
  d: path("M21 26.781c.25-1.515-.297-2.219-.297-2.219s-.234 1.141-.422 2.22c-.16.92-.531 2.562-.531 2.562s1-1.047 1.25-2.563");
}

.o2t45ac7v {
  fill: var(--svg-color--f9266d, #F9266D);
  d: path("M24.725 18.33a8.8 8.8 0 0 1-17.6 0c0-4.86 3.94-5.34 8.8-5.34s8.8.47 8.8 5.34");
}

.ofkxeblxx {
  stop-color: var(--svg-color--ff3887, #FF3887);
}

.onpxecnsg {
  stop-color: var(--svg-color--f0304b, #F0304B);
}

.oombh1b1l {
  stop-color: var(--svg-color--f02a32, #F02A32);
}

.op29lb3_e {
  stop-color: var(--svg-color--ed2554, #ED2554);
}

.oy5zpibej {
  fill: var(--svg-color--ff3b91, #FF3B91);
  d: path("M23.195 20.32c-.64 0-.93.78-.46 1.21a5.21 5.21 0 0 0 7.04 0c.47-.43.17-1.21-.46-1.21z");
}

.oz2kptbvf {
  stop-color: var(--svg-color--f5365a, #F5365A);
}

.p0etxehku {
  stop-color: var(--svg-color--716769, #716769);
}

.pbwjsnb0x {
  stop-color: var(--svg-color--ff7fa4, #FF7FA4);
}

.ptp8dmbsw {
  stop-color: var(--svg-color--ff40b5, #FF40B5);
}

.q_gqhe9iv {
  d: path("M23.925 18.48c-.45.45-.11 1.21.53 1.18c1.26-.05 2.5-.56 3.46-1.52s1.47-2.2 1.52-3.46c.03-.63-.73-.98-1.18-.53z");
}

.rvdkuw25u {
  stroke-linecap: round;
  d: path("M18.5 12.563v1.75");
}

.rve4g8b0f {
  d: path("M18.645 23.06a.695.695 0 0 1 1.19-.51c.88.9 1.45 2.11 1.5 3.47s-.42 2.61-1.24 3.57c-.41.48-1.2.22-1.22-.42z");
}

.s189hlbno {
  stop-color: var(--svg-color--ff238e, #FF238E);
  stop-opacity: 0;
}

.s4tq2tbyz {
  fill: var(--svg-color--ff4275, #FF4275);
  d: path("M23.095 11.54h1.84a.47.47 0 0 0 .481-.5a6.544 6.544 0 0 0-6.27-6.035a.243.243 0 0 0-.25.245v2.09a4.2 4.2 0 0 0 4.2 4.2");
}

.s7k3i1btx {
  stop-color: var(--svg-color--ff3fb1, #FF3FB1);
}

.s97one1oy {
  stop-color: var(--svg-color--ff37a2, #FF37A2);
}

.sij0lqbjd {
  stop-color: var(--svg-color--ff4aaf, #FF4AAF);
}

.smhq_hewq {
  stop-color: var(--svg-color--4b2a37, #4B2A37);
}

.ssla29buu {
  stop-color: var(--svg-color--fa1d84, #FA1D84);
}

.sypvssbqq {
  stop-color: var(--svg-color--ff687d, #FF687D);
}

.t07jf7kdj {
  stop-color: var(--svg-color--ff6ac1, #FF6AC1);
}

.t6dtxl50o {
  stop-color: var(--svg-color--c91589, #C91589);
}

.tpvcr5bus {
  stop-color: var(--svg-color--ff18a9, #FF18A9);
  stop-opacity: 0;
}

.tt7ka7bcu {
  d: path("M8.745 11.54h-1.83a.47.47 0 0 1-.481-.5a6.536 6.536 0 0 1 6.27-6.035a.243.243 0 0 1 .251.245v2.09c0 2.32-1.89 4.2-4.21 4.2");
}

.txvr8eipx {
  stop-color: var(--svg-color--ff23b1, #FF23B1);
  stop-opacity: 0;
}

.u3ub0_o0s {
  stop-color: var(--svg-color--ff608e, #FF608E);
  stop-opacity: 0;
}

.ui71nvg6n {
  d: path("M28.688 15.71c-.368.605-1.91 1.995-1.91 1.995c.248-.335.885-1.178 1.36-1.996c.425-.731.622-1.567.8-1.49c.376.163.117.885-.25 1.49");
}

.undnrubxu {
  stop-color: var(--svg-color--f3083a, #F3083A);
}

.uy7ti0b4p {
  stop-color: var(--svg-color--fc1c81, #FC1C81);
  stop-opacity: 0;
}

.vric1mb3o {
  stop-color: var(--svg-color--f3063b, #F3063B);
  stop-opacity: 0;
}

.vt6_nubcr {
  stop-color: var(--svg-color--ff607c, #FF607C);
}

.w_renqbra {
  d: path("M13.175 6.81h-.42v1.48h1.9c0-.82-.66-1.48-1.48-1.48");
}

.w0rqqac4v {
  stop-color: var(--svg-color--ff4570, #FF4570);
}

.wz7_3bkmz {
  d: path("M23.095 11.54h1.84a.47.47 0 0 0 .481-.5a6.544 6.544 0 0 0-6.27-6.035a.243.243 0 0 0-.25.245v2.09a4.2 4.2 0 0 0 4.2 4.2");
}

.wzh_6eg-b {
  stop-color: var(--svg-color--f75370, #F75370);
}

.xsvfp_f3u {
  d: path("M24.705 12.86a.98.98 0 1 0 0-1.96a.98.98 0 0 0 0 1.96");
}

.z0hrhzbme {
  d: path("M7.688 24.438c1.175-.989 2.453-.688 2.453-.688s-.903 1.038-1.735 1.75c-.71.608-1.932 1.765-1.932 1.765s.038-1.839 1.213-2.828");
}

.z3daj8abh {
  stop-color: var(--svg-color--ff6899, #FF6899);
  stop-opacity: 0;
}

.zov1arbng {
  stroke-linecap: round;
  d: path("M13.531 12.563v1.75");
}

.zrwonab6q {
  stop-color: var(--svg-color--fe8792, #FE8792);
}

.zyeypfbry {
  stop-color: var(--svg-color--ff436c, #FF436C);
}

</style>
