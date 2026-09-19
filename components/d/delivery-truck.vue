<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#igrZ8kb)"><path fill="url(#iB3L0Oc)" class="ailp3lfyr"/></g><path fill="url(#iqRa6Ic)" class="ailp3lfyr"/><path fill="url(#iy63Qvb)" class="ailp3lfyr"/><g filter="url(#ihg6YCb)"><path fill="url(#iroLtrd)" class="el9ld5q6k"/></g><path fill="url(#i2O13gt)" class="el9ld5q6k"/><path fill="url(#i6wNeOc)" class="el9ld5q6k"/><path fill="url(#iYSXDse)" class="donnfkrmf"/><path fill="url(#iR3DvlS)" class="donnfkrmf"/><path fill="url(#icK9Arb)" class="donnfkrmf"/><path fill="url(#iQ9v4Zm)" class="kffsgja_f"/><path fill="url(#iqDGWfd)" class="kffsgja_f"/><path fill="url(#iuvkC9c)" class="kffsgja_f"/><g filter="url(#iRUNSnc)"><path class="urw4zpbbu"/></g><path fill="url(#iWifZgx)" class="lwdf0zsgp"/><path fill="url(#iAjCdUd)" class="n528mkbtq"/><path fill="url(#iN3b5cc)" class="n528mkbtq"/><path fill="url(#i7CiRie)" class="n528mkbtq"/><path fill="url(#ih9DQZb)" class="n528mkbtq"/><path fill="url(#iZU53Cc)" clip-rule="evenodd" class="w6b7_ob2g"/><path fill="url(#iDC9bod)" clip-rule="evenodd" class="rdbwwqh4c"/><g filter="url(#iIBBIoc)"><path fill="url(#iKKhSjd)" class="yu1hn1uqz"/><path fill="url(#icWwfWc)" class="yu1hn1uqz"/></g><g filter="url(#irVqPZc)"><path class="if5td1bwt"/></g><path class="hwqae9biq"/><g filter="url(#if7obmc)"><path fill="url(#iAQUrKs)" class="j20ta7r2k"/><path fill="url(#iUuLNxb)" class="j20ta7r2k"/></g><g filter="url(#iSvSpEc)"><path class="f6xyq3y6j"/></g><g filter="url(#iQHfUZb)"><circle stroke="url(#iVMWgvd)" class="zt50j0s2m"/></g><g filter="url(#i5JJCYM)"><circle stroke="url(#iHEy27b)" class="ho2829b0t"/></g><defs><linearGradient id="iB3L0Oc" x1="2.461" x2="13.898" y1="16.073" y2="16.073" gradientUnits="userSpaceOnUse"><stop class="g5hs1h0pr"/><stop offset="1" class="a-r523h4s"/></linearGradient><linearGradient id="iqRa6Ic" x1="8.501" x2="8.501" y1="11.865" y2="12.632" gradientUnits="userSpaceOnUse"><stop class="qq1w9j3fl"/><stop offset=".495" class="ol65nac4d"/></linearGradient><linearGradient id="iy63Qvb" x1="13.898" x2="13.692" y1="15.81" y2="15.81" gradientUnits="userSpaceOnUse"><stop class="p9ory-bjp"/><stop offset="1" class="o_ms7tbkn"/></linearGradient><linearGradient id="iroLtrd" x1="14.659" x2="29.898" y1="21.026" y2="12.585" gradientUnits="userSpaceOnUse"><stop class="lu9nbtbhs"/><stop offset="1" class="v516l6bnp"/></linearGradient><linearGradient id="i2O13gt" x1="21.898" x2="21.898" y1="7.029" y2="9.119" gradientUnits="userSpaceOnUse"><stop class="bpxwb3rog"/><stop offset="1" class="ffn1n0s2j"/></linearGradient><linearGradient id="i6wNeOc" x1="29.898" x2="29.609" y1="15.154" y2="15.154" gradientUnits="userSpaceOnUse"><stop class="cd9h_obzw"/><stop offset="1" class="k9icqoi7i"/></linearGradient><linearGradient id="iYSXDse" x1="9.336" x2="3.273" y1="13.904" y2="19.029" gradientUnits="userSpaceOnUse"><stop class="ms-3iibbg"/><stop offset="1" class="vpc4a5zyy"/></linearGradient><linearGradient id="iR3DvlS" x1="6.053" x2="6.053" y1="13.039" y2="16.869" gradientUnits="userSpaceOnUse"><stop class="x6dmp79va"/><stop offset="1" class="mnh30mbbs"/></linearGradient><linearGradient id="icK9Arb" x1="10.312" x2="8.883" y1="16.552" y2="16.552" gradientUnits="userSpaceOnUse"><stop class="vadls4byn"/><stop offset="1" class="ll1lvcbwu"/></linearGradient><linearGradient id="iQ9v4Zm" x1="18.728" x2="18.773" y1="20.024" y2="26.091" gradientUnits="userSpaceOnUse"><stop class="jxk4su0oc"/><stop offset="1" class="x9e4xlp6m"/></linearGradient><linearGradient id="iqDGWfd" x1="13.898" x2="14.999" y1="22.614" y2="22.614" gradientUnits="userSpaceOnUse"><stop offset=".513" class="o-6uytbym"/><stop offset="1" class="qis8ae1wi"/></linearGradient><linearGradient id="iuvkC9c" x1="21.898" x2="21.898" y1="27.899" y2="25.336" gradientUnits="userSpaceOnUse"><stop class="yl2dfh2fq"/><stop offset="1" class="w9yxb93dk"/></linearGradient><linearGradient id="iWifZgx" x1="27.896" x2="29.492" y1="22.591" y2="24.435" gradientUnits="userSpaceOnUse"><stop class="shkvo86_r"/><stop offset="1" class="q7-uwpbqz"/></linearGradient><linearGradient id="iAjCdUd" x1="7.898" x2="7.898" y1="19.591" y2="27.039" gradientUnits="userSpaceOnUse"><stop class="sdb1scbzi"/><stop offset="1" class="ghzd3_bys"/></linearGradient><linearGradient id="iN3b5cc" x1="13.898" x2="12.054" y1="23.685" y2="23.685" gradientUnits="userSpaceOnUse"><stop class="nrwrfok0v"/><stop offset="1" class="ydln8ob2s"/></linearGradient><linearGradient id="i7CiRie" x1="7.898" x2="7.898" y1="27.039" y2="25.341" gradientUnits="userSpaceOnUse"><stop class="yl2dfh2fq"/><stop offset="1" class="w9yxb93dk"/></linearGradient><linearGradient id="ih9DQZb" x1="13.898" x2="13.692" y1="22.696" y2="22.696" gradientUnits="userSpaceOnUse"><stop class="r8hxslboo"/><stop offset="1" class="ou02lkevj"/></linearGradient><linearGradient id="iZU53Cc" x1="8.599" x2="8.599" y1="22.616" y2="27.039" gradientUnits="userSpaceOnUse"><stop class="repvx5bvm"/><stop offset="1" class="yb9qpebjt"/></linearGradient><linearGradient id="iDC9bod" x1="23.398" x2="23.398" y1="22.616" y2="27.039" gradientUnits="userSpaceOnUse"><stop class="repvx5bvm"/><stop offset="1" class="yb9qpebjt"/></linearGradient><linearGradient id="iKKhSjd" x1="21.827" x2="27.04" y1="25.656" y2="25.656" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iAQUrKs" x1="6.998" x2="12.212" y1="25.656" y2="25.656" gradientUnits="userSpaceOnUse"><stop offset=".239" class="baem9ki2q"/><stop offset="1" class="mmwl-dsmc"/></linearGradient><linearGradient id="iVMWgvd" x1="10.061" x2="7.15" y1="24.286" y2="28.307" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><linearGradient id="iHEy27b" x1="24.933" x2="22.021" y1="24.286" y2="28.307" gradientUnits="userSpaceOnUse"><stop offset=".083" class="oeptinb4s"/><stop offset=".391" class="f0k16nibb"/><stop offset=".692" class="f0k16nibb"/><stop offset=".935" class="oeptinb4s"/></linearGradient><filter id="igrZ8kb" width="13" height="10.137" x="1.398" y="12.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.945098 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.639216 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10756" result="effect2_innerShadow_18_10756"/></filter><filter id="ihg6YCb" width="17" height="14.251" x="13.398" y="7.029" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".8"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.615686 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.756863 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10756" result="effect2_innerShadow_18_10756"/></filter><filter id="iRUNSnc" width="3.1" height="3.1" x="21.848" y="24.979" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10756" result="effect2_innerShadow_18_10756"/></filter><filter id="iIBBIoc" width="6.942" height="7.092" x="19.956" y="23.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10756" result="effect2_innerShadow_18_10756"/></filter><filter id="irVqPZc" width="2.662" height="2.662" x="22.098" y="25.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10756" result="effect2_innerShadow_18_10756"/></filter><filter id="if7obmc" width="6.942" height="7.092" x="5.128" y="23.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0823529 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0313726 0 0 0 0 0.235294 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10756" result="effect2_innerShadow_18_10756"/></filter><filter id="iSvSpEc" width="2.662" height="2.662" x="7.27" y="25.198" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".05" dy="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.364706 0 0 0 0 0.584314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10756"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05" dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.764706 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_10756" result="effect2_innerShadow_18_10756"/></filter><filter id="iQHfUZb" width="7.143" height="7.143" x="5.184" y="22.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10756" stdDeviation=".375"/></filter><filter id="i5JJCYM" width="7.143" height="7.143" x="20.055" y="22.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10756" stdDeviation=".375"/></filter><radialGradient id="icWwfWc" cx="0" cy="0" r="1" gradientTransform="matrix(.7843 -1.7239 1.80055 .81917 23.427 26.218)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient><radialGradient id="iUuLNxb" cx="0" cy="0" r="1" gradientTransform="matrix(.7843 -1.7239 1.80055 .81917 8.599 26.218)" gradientUnits="userSpaceOnUse"><stop offset=".523" class="ariye-f8h"/><stop offset="1" class="a2peghb2c"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:delivery-truck" /></template>
<style>
.a-r523h4s {
  stop-color: var(--svg-color--ebddf3, #EBDDF3);
}

.a2peghb2c {
  stop-color: var(--svg-color--2b1249, #2B1249);
  stop-opacity: 0;
}

.ailp3lfyr {
  d: path("m2.058 19.329l3.37-6.41c.29-.55.86-.89 1.48-.89h6.84a.15.15 0 0 1 .15.15v9.787l-12-1.847c0-.27.05-.54.16-.79");
}

.ariye-f8h {
  stop-color: var(--svg-color--2d114d, #2D114D);
}

.baem9ki2q {
  stop-color: var(--svg-color--34214f, #34214F);
}

.bpxwb3rog {
  stop-color: var(--svg-color--eac439, #EAC439);
}

.cd9h_obzw {
  stop-color: var(--svg-color--ddbe7a, #DDBE7A);
}

.donnfkrmf {
  d: path("M2.208 19.029h6.59c.61 0 1.1-.49 1.1-1.1v-3.79c0-.61-.49-1.1-1.1-1.1h-3.42z");
}

.el9ld5q6k {
  d: path("M26.898 7.029h-10c-1.66 0-3 1.34-3 3V21.28h16V10.03c0-1.66-1.34-3-3-3");
}

.f0k16nibb {
  stop-color: var(--svg-color--615b6b, #615B6B);
  stop-opacity: 0;
}

.f6xyq3y6j {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M8.601 27.81a1.281 1.281 0 1 0 0-2.562a1.281 1.281 0 0 0 0 2.562");
}

.ffn1n0s2j {
  stop-color: var(--svg-color--eac439, #EAC439);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g5hs1h0pr {
  stop-color: var(--svg-color--c9bdd1, #C9BDD1);
}

.ghzd3_bys {
  stop-color: var(--svg-color--ee3124, #EE3124);
}

.ho2829b0t {
  cx: 23.627px;
  cy: 26.188px;
  r: 2.397px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

.hwqae9biq {
  fill: var(--svg-color--f8da4b, #F8DA4B);
  d: path("M2.808 25.029h-.91v-4h.91c.6 0 1.09.49 1.09 1.09v1.82c0 .6-.49 1.09-1.09 1.09");
}

.if5td1bwt {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M23.43 27.81a1.281 1.281 0 1 0 0-2.562a1.281 1.281 0 0 0 0 2.562");
}

.j20ta7r2k {
  d: path("M8.599 30a3.471 3.471 0 1 0 0-6.942a3.471 3.471 0 0 0 0 6.942");
}

.jxk4su0oc {
  stop-color: var(--svg-color--fd6e33, #FD6E33);
}

.k9icqoi7i {
  stop-color: var(--svg-color--ddbe7a, #DDBE7A);
  stop-opacity: 0;
}

.kffsgja_f {
  d: path("M13.898 27.034v-7.01h16v5.21c0 .99-.81 1.8-1.8 1.8z");
}

.ll1lvcbwu {
  stop-color: var(--svg-color--48b8e6, #48B8E6);
  stop-opacity: 0;
}

.lu9nbtbhs {
  stop-color: var(--svg-color--f1c147, #F1C147);
}

.lwdf0zsgp {
  d: path("M29.898 22.029h-.5c-.85 0-1.54.71-1.5 1.57c.04.81.74 1.43 1.55 1.43h.45z");
}

.mmwl-dsmc {
  stop-color: var(--svg-color--241337, #241337);
}

.mnh30mbbs {
  stop-color: var(--svg-color--1d95dd, #1D95DD);
  stop-opacity: 0;
}

.ms-3iibbg {
  stop-color: var(--svg-color--35a5e2, #35A5E2);
}

.n528mkbtq {
  d: path("M13.898 20.029h-12v5.23c0 .98.8 1.78 1.78 1.78h10.22z");
}

.nrwrfok0v {
  stop-color: var(--svg-color--ff7b3d, #FF7B3D);
}

.o_ms7tbkn {
  stop-color: var(--svg-color--604114, #604114);
  stop-opacity: 0;
}

.o-6uytbym {
  stop-color: var(--svg-color--ea3a0c, #EA3A0C);
}

.oeptinb4s {
  stop-color: var(--svg-color--615b6b, #615B6B);
}

.ol65nac4d {
  stop-color: var(--svg-color--c8c6c5, #C8C6C5);
  stop-opacity: 0;
}

.ou02lkevj {
  stop-color: var(--svg-color--bc2303, #BC2303);
  stop-opacity: 0;
}

.p9ory-bjp {
  stop-color: var(--svg-color--604114, #604114);
}

.q7-uwpbqz {
  stop-color: var(--svg-color--c8166a, #C8166A);
}

.qis8ae1wi {
  stop-color: var(--svg-color--ea3a0c, #EA3A0C);
  stop-opacity: 0;
}

.qq1w9j3fl {
  stop-color: var(--svg-color--c8c6c5, #C8C6C5);
}

.r8hxslboo {
  stop-color: var(--svg-color--bc2303, #BC2303);
}

.rdbwwqh4c {
  fill-rule: evenodd;
  d: path("M27.278 27.039q.033-.25.033-.51a3.913 3.913 0 1 0-7.793.51z");
}

.repvx5bvm {
  stop-color: var(--svg-color--99160c, #99160C);
}

.sdb1scbzi {
  stop-color: var(--svg-color--ff7233, #FF7233);
}

.shkvo86_r {
  stop-color: var(--svg-color--bd0663, #BD0663);
}

.urw4zpbbu {
  fill: var(--svg-color--d9c3f0, #D9C3F0);
  d: path("M23.398 28.029a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.v516l6bnp {
  stop-color: var(--svg-color--e0b343, #E0B343);
}

.vadls4byn {
  stop-color: var(--svg-color--48b8e6, #48B8E6);
}

.vpc4a5zyy {
  stop-color: var(--svg-color--4ad3f9, #4AD3F9);
}

.w6b7_ob2g {
  fill-rule: evenodd;
  d: path("M12.479 27.039q.033-.25.033-.51a3.913 3.913 0 1 0-7.793.51z");
}

.w9yxb93dk {
  stop-color: var(--svg-color--bc2447, #BC2447);
  stop-opacity: 0;
}

.x6dmp79va {
  stop-color: var(--svg-color--1d95dd, #1D95DD);
}

.x9e4xlp6m {
  stop-color: var(--svg-color--eb3c3d, #EB3C3D);
}

.yb9qpebjt {
  stop-color: var(--svg-color--ac0819, #AC0819);
}

.ydln8ob2s {
  stop-color: var(--svg-color--ff7b3d, #FF7B3D);
  stop-opacity: 0;
}

.yl2dfh2fq {
  stop-color: var(--svg-color--bc2447, #BC2447);
}

.yu1hn1uqz {
  d: path("M23.427 30a3.471 3.471 0 1 0 0-6.942a3.471 3.471 0 0 0 0 6.942");
}

.zt50j0s2m {
  cx: 8.756px;
  cy: 26.188px;
  r: 2.397px;
  stroke-width: var(--svg-stroke-width--0-85px, 0.85px);
}

</style>
