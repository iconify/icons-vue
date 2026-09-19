<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iYPi3ob)" class="r7j9bcbay"><path class="v1_mknbqm"/><path stroke="url(#iepIYtc)" class="wx0ewqwux"/></g><path stroke="url(#iy8UPfe)" class="o1n23cc3a"/><g filter="url(#iiuIscc)" class="r7j9bcbay"><path class="qmd3l6nqw"/><path stroke="url(#iHwuMAc)" class="efd3s6b_o"/></g><path stroke="url(#iVNmGie)" class="val6h-bsw"/><path stroke="url(#iLIFh3d)" class="s1cetpb7t"/><path stroke="url(#iMIpW2b)" class="s1cetpb7t"/><path stroke="url(#iOKwLEe)" class="ozuj9nf_v"/><path stroke="url(#i9Y2Bow)" class="o1nxl62bj"/><g filter="url(#ihDe6xb)"><path class="r7i3p-b7a"/></g><path stroke="url(#ivA1y4c)" class="p12mdlb_v"/><path stroke="url(#iguZKDb)" class="p12mdlb_v"/><circle fill="url(#i5k3hNe)" class="gjkmphmnk"/><circle fill="url(#iRqdMOb)" class="gjkmphmnk"/><circle fill="url(#iinm6Uc)" class="gjkmphmnk"/><path fill="url(#i1J1Vme)" class="nf-7iibpq"/><path fill="url(#iChgfFb)" class="nf-7iibpq"/><path fill="url(#iZxJCMd)" class="nf-7iibpq"/><path fill="url(#iJyOufe)" class="nf-7iibpq"/><path fill="url(#i4oyjUd)" class="nf-7iibpq"/><path fill="url(#imz3rxb)" class="nf-7iibpq"/><path stroke="url(#iq0sDEd)" class="r6ta55i_u"/><g filter="url(#i3hVzSm)"><path class="fvrj28bcs"/></g><path fill="url(#ijmzggc)" class="dtag3ybxs"/><path fill="url(#iVGPsfb)" class="dtag3ybxs"/><path fill="url(#iRro81c)" class="dtag3ybxs"/><path fill="url(#i3zygUc)" class="dtag3ybxs"/><path fill="url(#ikkjxOc)" class="dtag3ybxs"/><path fill="url(#iG6qEwb)" class="dtag3ybxs"/><circle fill="url(#ivFMGOb)" class="dg7gb6b8w"/><circle fill="url(#il5FlUc)" class="dg7gb6b8w"/><circle fill="url(#iZj9Pqe)" class="dg7gb6b8w"/><g filter="url(#iwbG0vd)"><path stroke="url(#ixsf0ne)" class="ddc3ebdsa"/></g><path stroke="url(#iNS0CLg)" class="hnacuv8za"/><path stroke="url(#i4GLYtd)" class="hnacuv8za"/><path stroke="url(#i6VfjrL)" class="hnacuv8za"/><path stroke="url(#iNGzROb)" class="hnacuv8za"/><path stroke="url(#iLZ9jLb)" class="hnacuv8za"/><path fill="url(#iTdJWXb)" class="p9m4_9xdw"/><path fill="url(#iXpuaxN)" class="p9m4_9xdw"/><path fill="url(#iH31cJc)" class="p9m4_9xdw"/><path fill="url(#i9miz4c)" class="p9m4_9xdw"/><path fill="url(#iMNXtBc)" class="p9m4_9xdw"/><g filter="url(#ixwDYVO)"><path stroke="url(#iqlQKpb)" class="tj0k2rbvy"/></g><circle fill="url(#iQt581c)" class="fvpebvp_i"/><circle fill="url(#i9Qa0rd)" class="fvpebvp_i"/><circle fill="url(#iNqwclc)" class="fvpebvp_i"/><defs><radialGradient id="iepIYtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 0 0 2.47157 9.248 11.028)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="rrtlwlbyp"/><stop offset="1" class="xdxs5j-ne"/></radialGradient><radialGradient id="iy8UPfe" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -4.125 3.1941 3.96843 10.487 11.938)" gradientUnits="userSpaceOnUse"><stop offset=".726" class="ji46adcbc"/><stop offset=".988" class="dd8emhm-w"/></radialGradient><radialGradient id="iHwuMAc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40625 0 0 -2.47157 22.768 11.028)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="rrtlwlbyp"/><stop offset="1" class="xdxs5j-ne"/></radialGradient><radialGradient id="i5k3hNe" cx="0" cy="0" r="1" gradientTransform="rotate(110.554 8.92 13.723)scale(2.60891 2.71579)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="s3ygq5put"/><stop offset="1" class="tlape8e_o"/></radialGradient><radialGradient id="iRqdMOb" cx="0" cy="0" r="1" gradientTransform="rotate(134.483 10.685 10.428)scale(1.78636 1.9273)" gradientUnits="userSpaceOnUse"><stop class="h00tvm1qa"/><stop offset="1" class="us8k5y62k"/></radialGradient><radialGradient id="iinm6Uc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37105 1.18631 0 23.985 12.834)" gradientUnits="userSpaceOnUse"><stop class="qrigk3b3s"/><stop offset="1" class="o9e9hacmt"/></radialGradient><radialGradient id="i1J1Vme" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.80267 -8.93422 0 23.985 20.188)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="s9qtfjt1m"/><stop offset="1" class="i5-6o0bbs"/></radialGradient><radialGradient id="iZxJCMd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28126 4.375 -2.905 -2.17876 28.676 19.438)" gradientUnits="userSpaceOnUse"><stop class="li8yaactd"/><stop offset="1" class="bejy_p2rm"/></radialGradient><radialGradient id="iJyOufe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.49017 -8.65297 0 23.985 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".592" class="eqhbsgb5r"/><stop offset="1" class="ugq9daboy"/></radialGradient><radialGradient id="i4oyjUd" cx="0" cy="0" r="1" gradientTransform="rotate(52.677 -8.388 32.667)scale(7.11272 9.92047)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="lk3-h7bzt"/><stop offset="1" class="a0vs3fb6x"/></radialGradient><radialGradient id="imz3rxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -8.32499 0 27.988 20.5)" gradientUnits="userSpaceOnUse"><stop class="ld0lxubsr"/><stop offset="1" class="vc4skwghs"/></radialGradient><radialGradient id="ijmzggc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.80267 -8.93422 0 8.015 20.188)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="s9qtfjt1m"/><stop offset="1" class="i5-6o0bbs"/></radialGradient><radialGradient id="iRro81c" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28126 4.375 -2.905 -2.17876 12.706 19.438)" gradientUnits="userSpaceOnUse"><stop class="li8yaactd"/><stop offset="1" class="bejy_p2rm"/></radialGradient><radialGradient id="i3zygUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.125 -8.32499 0 12.018 20.5)" gradientUnits="userSpaceOnUse"><stop class="ld0lxubsr"/><stop offset="1" class="vc4skwghs"/></radialGradient><radialGradient id="ikkjxOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.49017 -8.65297 0 8.015 20.5)" gradientUnits="userSpaceOnUse"><stop offset=".592" class="eqhbsgb5r"/><stop offset="1" class="ugq9daboy"/></radialGradient><radialGradient id="iG6qEwb" cx="0" cy="0" r="1" gradientTransform="rotate(52.677 -16.373 16.538)scale(7.11272 9.92047)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="lk3-h7bzt"/><stop offset="1" class="a0vs3fb6x"/></radialGradient><radialGradient id="ivFMGOb" cx="0" cy="0" r="1" gradientTransform="rotate(110.554 .935 8.189)scale(2.60891 2.71579)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="s3ygq5put"/><stop offset="1" class="tlape8e_o"/></radialGradient><radialGradient id="il5FlUc" cx="0" cy="0" r="1" gradientTransform="rotate(134.483 2.7 7.078)scale(1.78636 1.9273)" gradientUnits="userSpaceOnUse"><stop class="h00tvm1qa"/><stop offset="1" class="us8k5y62k"/></radialGradient><radialGradient id="iZj9Pqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37105 1.18631 0 8.015 12.834)" gradientUnits="userSpaceOnUse"><stop class="qrigk3b3s"/><stop offset="1" class="o9e9hacmt"/></radialGradient><radialGradient id="i4GLYtd" cx="0" cy="0" r="1" gradientTransform="rotate(117.255 6.37 7.125)scale(2.15051 1.22508)" gradientUnits="userSpaceOnUse"><stop class="az7w1qbqf"/><stop offset="1" class="pn0f51-jz"/></radialGradient><radialGradient id="iLZ9jLb" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.473 -5.94303 0 16 12.188)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="nrqr_154x"/><stop offset="1" class="ek0jtmn9y"/></radialGradient><radialGradient id="iXpuaxN" cx="0" cy="0" r="1" gradientTransform="matrix(-7.42474 0 0 -2.6875 23.425 29.75)" gradientUnits="userSpaceOnUse"><stop class="uy4jqwbvr"/><stop offset="1" class="ux9b5bcuc"/></radialGradient><radialGradient id="i9miz4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.68751 -5.375 15.5425 -4.87966 15.362 30.969)" gradientUnits="userSpaceOnUse"><stop offset=".57" class="kuf_ldbxf"/><stop offset="1" class="o5mhlqbpq"/></radialGradient><radialGradient id="iMNXtBc" cx="0" cy="0" r="1" gradientTransform="matrix(.00003 -3.75 12.8622 .00009 16 29.375)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="trns_kb3w"/><stop offset="1" class="kls_f9qyb"/></radialGradient><radialGradient id="iQt581c" cx="0" cy="0" r="1" gradientTransform="rotate(110.554 7.47 7.287)scale(2.60891 2.71579)" gradientUnits="userSpaceOnUse"><stop offset=".319" class="s3ygq5put"/><stop offset="1" class="tlape8e_o"/></radialGradient><radialGradient id="i9Qa0rd" cx="0" cy="0" r="1" gradientTransform="rotate(134.483 8.232 5.084)scale(1.78636 1.9273)" gradientUnits="userSpaceOnUse"><stop class="h00tvm1qa"/><stop offset="1" class="us8k5y62k"/></radialGradient><radialGradient id="iNqwclc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.37105 1.18631 0 16 5.496)" gradientUnits="userSpaceOnUse"><stop class="qrigk3b3s"/><stop offset="1" class="o9e9hacmt"/></radialGradient><linearGradient id="iVNmGie" x1="7.425" x2="8.862" y1="18.031" y2="18.063" gradientUnits="userSpaceOnUse"><stop offset=".188" class="h6-bc57zo"/><stop offset="1" class="k85hzjs6k"/></linearGradient><linearGradient id="iLIFh3d" x1="10.503" x2="11.237" y1="16.334" y2="15.813" gradientUnits="userSpaceOnUse"><stop offset=".175" class="y-d2mcc2x"/><stop offset="1" class="r8_-3nkvf"/></linearGradient><linearGradient id="iMIpW2b" x1="10.331" x2="10.53" y1="16.395" y2="16.266" gradientUnits="userSpaceOnUse"><stop class="czd50or1g"/><stop offset="1" class="ycu68kbag"/></linearGradient><linearGradient id="iOKwLEe" x1="23.348" x2="24.785" y1="18.031" y2="18.063" gradientUnits="userSpaceOnUse"><stop offset=".188" class="h6-bc57zo"/><stop offset="1" class="k85hzjs6k"/></linearGradient><linearGradient id="i9Y2Bow" x1="20.473" x2="21.442" y1="16.334" y2="17.031" gradientUnits="userSpaceOnUse"><stop class="q1u9kybft"/><stop offset="1" class="rs4dv1bhf"/></linearGradient><linearGradient id="ivA1y4c" x1="26.426" x2="27.16" y1="16.334" y2="15.813" gradientUnits="userSpaceOnUse"><stop offset=".175" class="y-d2mcc2x"/><stop offset="1" class="r8_-3nkvf"/></linearGradient><linearGradient id="iguZKDb" x1="26.254" x2="26.453" y1="16.395" y2="16.266" gradientUnits="userSpaceOnUse"><stop class="czd50or1g"/><stop offset="1" class="ycu68kbag"/></linearGradient><linearGradient id="iChgfFb" x1="23.985" x2="23.985" y1="19.998" y2="21.156" gradientUnits="userSpaceOnUse"><stop class="km34w7oco"/><stop offset="1" class="fpz_x6b_q"/></linearGradient><linearGradient id="iq0sDEd" x1="4.55" x2="5.518" y1="16.334" y2="17.031" gradientUnits="userSpaceOnUse"><stop class="q1u9kybft"/><stop offset="1" class="rs4dv1bhf"/></linearGradient><linearGradient id="iVGPsfb" x1="8.015" x2="8.015" y1="19.998" y2="21.156" gradientUnits="userSpaceOnUse"><stop class="km34w7oco"/><stop offset="1" class="fpz_x6b_q"/></linearGradient><linearGradient id="ixsf0ne" x1="16.362" x2="19.421" y1="7.757" y2="11.981" gradientUnits="userSpaceOnUse"><stop class="foteutbvm"/><stop offset="1" class="kvbhp09bi"/></linearGradient><linearGradient id="iNS0CLg" x1="15.255" x2="16.375" y1="13.896" y2="13.896" gradientUnits="userSpaceOnUse"><stop class="hkaq_6w3b"/><stop offset="1" class="jolru5b2r"/></linearGradient><linearGradient id="i6VfjrL" x1="15.294" x2="15.294" y1="26.294" y2="20.925" gradientUnits="userSpaceOnUse"><stop class="e71pccrml"/><stop offset="1" class="lelz7zbug"/></linearGradient><linearGradient id="iNGzROb" x1="15.151" x2="15.503" y1="16" y2="16" gradientUnits="userSpaceOnUse"><stop class="m1cq8obrg"/><stop offset="1" class="b6z4tza6x"/></linearGradient><linearGradient id="iTdJWXb" x1="16" x2="16" y1="25.907" y2="29.719" gradientUnits="userSpaceOnUse"><stop offset=".254" class="jtf0qhbez"/><stop offset=".754" class="i0kb0tsfp"/></linearGradient><linearGradient id="iH31cJc" x1="17.675" x2="17.675" y1="29.963" y2="29.219" gradientUnits="userSpaceOnUse"><stop class="isg19pbuf"/><stop offset="1" class="n1upd3ncp"/></linearGradient><linearGradient id="iqlQKpb" x1="16.893" x2="16.893" y1="4.906" y2="22.031" gradientUnits="userSpaceOnUse"><stop class="sfk_7tb8x"/><stop offset="1" class="ja04qgk0z"/></linearGradient><filter id="iYPi3ob" width="8.917" height="5.859" x="7.765" y="5.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.588235 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24521"/></filter><filter id="iiuIscc" width="8.917" height="5.859" x="15.335" y="5.869" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.682353 0 0 0 0 0.588235 0 0 0 0 0.694118 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24521"/></filter><filter id="ihDe6xb" width="6.215" height="9.208" x="18.073" y="11.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24521" stdDeviation=".2"/></filter><filter id="i3hVzSm" width="6.215" height="9.208" x="2.306" y="11.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24521" stdDeviation=".2"/></filter><filter id="iwbG0vd" width="3.966" height="5.013" x="15.856" y="6.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24521" stdDeviation=".2"/></filter><filter id="ixwDYVO" width="1.2" height="17.925" x="15.793" y="4.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24521" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:balance-scale" /></template>
<style>
.a0vs3fb6x {
  stop-color: var(--svg-color--e29471, #E29471);
}

.az7w1qbqf {
  stop-color: var(--svg-color--b59cad, #B59CAD);
}

.b6z4tza6x {
  stop-color: var(--svg-color--cbb6ca, #CBB6CA);
  stop-opacity: 0;
}

.bejy_p2rm {
  stop-color: var(--svg-color--ffc635, #FFC635);
  stop-opacity: 0;
}

.czd50or1g {
  stop-color: var(--svg-color--c2a6b1, #C2A6B1);
}

.dd8emhm-w {
  stop-color: var(--svg-color--99839c, #99839C);
}

.ddc3ebdsa {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m16.456 6.953l2.766 3.813");
}

.dg7gb6b8w {
  cx: 8.015px;
  cy: 11.004px;
  r: 1.627px;
}

.dtag3ybxs {
  d: path("M2.626 19.998c-.415 0-.724.384-.586.775a6.341 6.341 0 0 0 11.95 0c.139-.39-.17-.775-.585-.775z");
}

.e71pccrml {
  stop-color: var(--svg-color--bc9ea3, #BC9EA3);
}

.efd3s6b_o {
  d: path("M23.752 11.028h-4.26a1 1 0 0 1-.81-.413l-2.78-3.835");
}

.ek0jtmn9y {
  stop-color: var(--svg-color--92767e, #92767E);
}

.eqhbsgb5r {
  stop-color: var(--svg-color--fd9860, #FD9860);
  stop-opacity: 0;
}

.foteutbvm {
  stop-color: var(--svg-color--fdebff, #FDEBFF);
}

.fpz_x6b_q {
  stop-color: var(--svg-color--ffcf4d, #FFCF4D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvpebvp_i {
  cx: 16px;
  cy: 3.666px;
  r: 1.627px;
}

.fvrj28bcs {
  stroke: var(--svg-color--f8dde7, #F8DDE7);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m2.812 20.472l5.203-8.275");
}

.gjkmphmnk {
  cx: 23.985px;
  cy: 11.004px;
  r: 1.627px;
}

.h00tvm1qa {
  stop-color: var(--svg-color--fff361, #FFF361);
}

.h6-bc57zo {
  stop-color: var(--svg-color--bba1b3, #BBA1B3);
}

.hkaq_6w3b {
  stop-color: var(--svg-color--c3aec2, #C3AEC2);
}

.hnacuv8za {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16 4.376V26.66");
}

.i0kb0tsfp {
  stop-color: var(--svg-color--ffce37, #FFCE37);
}

.i5-6o0bbs {
  stop-color: var(--svg-color--ff9d5b, #FF9D5B);
}

.isg19pbuf {
  stop-color: var(--svg-color--fa8694, #FA8694);
}

.ja04qgk0z {
  stop-color: var(--svg-color--edd9ee, #EDD9EE);
  stop-opacity: 0;
}

.ji46adcbc {
  stop-color: var(--svg-color--99839c, #99839C);
  stop-opacity: 0;
}

.jolru5b2r {
  stop-color: var(--svg-color--e7d3e6, #E7D3E6);
}

.jtf0qhbez {
  stop-color: var(--svg-color--f9c63c, #F9C63C);
}

.k85hzjs6k {
  stop-color: var(--svg-color--d7b7c8, #D7B7C8);
}

.kls_f9qyb {
  stop-color: var(--svg-color--d29f5f, #D29F5F);
}

.km34w7oco {
  stop-color: var(--svg-color--ffcf4d, #FFCF4D);
}

.kuf_ldbxf {
  stop-color: var(--svg-color--eb9e40, #EB9E40);
  stop-opacity: 0;
}

.kvbhp09bi {
  stop-color: var(--svg-color--fdebff, #FDEBFF);
  stop-opacity: 0;
}

.ld0lxubsr {
  stop-color: var(--svg-color--fff263, #FFF263);
}

.lelz7zbug {
  stop-color: var(--svg-color--bc9ea3, #BC9EA3);
  stop-opacity: 0;
}

.li8yaactd {
  stop-color: var(--svg-color--ffc635, #FFC635);
}

.lk3-h7bzt {
  stop-color: var(--svg-color--ffb651, #FFB651);
  stop-opacity: 0;
}

.m1cq8obrg {
  stop-color: var(--svg-color--a38b8f, #A38B8F);
}

.n1upd3ncp {
  stop-color: var(--svg-color--ffa166, #FFA166);
  stop-opacity: 0;
}

.nf-7iibpq {
  d: path("M18.595 19.998c-.414 0-.724.384-.585.775a6.341 6.341 0 0 0 11.95 0c.139-.39-.171-.775-.585-.775z");
}

.nrqr_154x {
  stop-color: var(--svg-color--92767e, #92767E);
  stop-opacity: 0;
}

.o1n23cc3a {
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
  d: path("M8.265 11.028h4.26a1 1 0 0 0 .809-.413l2.78-3.835");
}

.o1nxl62bj {
  d: path("m18.578 20.472l5.204-8.275");
}

.o5mhlqbpq {
  stop-color: var(--svg-color--eb9e40, #EB9E40);
}

.o9e9hacmt {
  stop-color: var(--svg-color--e98856, #E98856);
  stop-opacity: 0;
}

.ozuj9nf_v {
  d: path("M23.956 12.197v8.748");
}

.p12mdlb_v {
  d: path("m29.392 20.472l-5.204-8.275");
}

.p9m4_9xdw {
  d: path("M23.19 29.963c.64 0 .967-.737.485-1.16A11.58 11.58 0 0 0 16 25.906a11.58 11.58 0 0 0-7.676 2.895c-.48.424-.155 1.16.486 1.16z");
}

.pn0f51-jz {
  stop-color: var(--svg-color--b59cad, #B59CAD);
  stop-opacity: 0;
}

.q1u9kybft {
  stop-color: var(--svg-color--c1afc0, #C1AFC0);
}

.qmd3l6nqw {
  stroke: var(--svg-color--d2c2d4, #D2C2D4);
  d: path("M23.752 11.028h-4.26a1 1 0 0 1-.81-.413l-2.78-3.835");
}

.qrigk3b3s {
  stop-color: var(--svg-color--e98856, #E98856);
}

.r6ta55i_u {
  d: path("m2.655 20.472l5.204-8.275");
}

.r7i3p-b7a {
  stroke: var(--svg-color--f8dde7, #F8DDE7);
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m18.578 20.472l5.204-8.275");
}

.r7j9bcbay {
  stroke-width: var(--svg-stroke-width--1-4px, 1.4px);
}

.r8_-3nkvf {
  stop-color: var(--svg-color--e6d2e4, #E6D2E4);
}

.rrtlwlbyp {
  stop-color: var(--svg-color--bdaab9, #BDAAB9);
}

.rs4dv1bhf {
  stop-color: var(--svg-color--f6d6de, #F6D6DE);
}

.s1cetpb7t {
  d: path("m13.468 20.472l-5.203-8.275");
}

.s3ygq5put {
  stop-color: var(--svg-color--ffc539, #FFC539);
}

.s9qtfjt1m {
  stop-color: var(--svg-color--ffb85e, #FFB85E);
}

.sfk_7tb8x {
  stop-color: var(--svg-color--edd9ee, #EDD9EE);
}

.tj0k2rbvy {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.393 4.906v17.125");
}

.tlape8e_o {
  stop-color: var(--svg-color--f6973e, #F6973E);
}

.trns_kb3w {
  stop-color: var(--svg-color--ddb761, #DDB761);
  stop-opacity: 0;
}

.ugq9daboy {
  stop-color: var(--svg-color--f18e9d, #F18E9D);
}

.us8k5y62k {
  stop-color: var(--svg-color--fff361, #FFF361);
  stop-opacity: 0;
}

.ux9b5bcuc {
  stop-color: var(--svg-color--ffff64, #FFFF64);
  stop-opacity: 0;
}

.uy4jqwbvr {
  stop-color: var(--svg-color--ffff64, #FFFF64);
}

.v1_mknbqm {
  stroke: var(--svg-color--d2c2d4, #D2C2D4);
  d: path("M8.265 11.028h4.26a1 1 0 0 0 .809-.413l2.78-3.835");
}

.val6h-bsw {
  d: path("M8.033 12.197v8.748");
}

.vc4skwghs {
  stop-color: var(--svg-color--ffd049, #FFD049);
  stop-opacity: 0;
}

.wx0ewqwux {
  d: path("M8.265 11.028h4.26a1 1 0 0 0 .809-.413l2.78-3.835");
}

.xdxs5j-ne {
  stop-color: var(--svg-color--bdaab9, #BDAAB9);
  stop-opacity: 0;
}

.y-d2mcc2x {
  stop-color: var(--svg-color--d0b6c3, #D0B6C3);
}

.ycu68kbag {
  stop-color: var(--svg-color--c2a6b1, #C2A6B1);
  stop-opacity: 0;
}

</style>
