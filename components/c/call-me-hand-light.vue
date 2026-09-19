<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i7GsqVd)"><path fill="url(#iB4lHPc)" class="ujydyib8d"/><path fill="url(#iYETYDy)" class="ujydyib8d"/><path fill="url(#izPj1Pb)" class="ujydyib8d"/></g><path fill="url(#i7ySpsf)" class="ujydyib8d"/><g filter="url(#iedevSc)"><path fill="url(#iHc8ZEd)" class="ueos9yy2y"/></g><rect fill="url(#iEgD3td)" class="zys7f72ey"/><rect fill="url(#iFO5K3d)" class="qxrjxujji"/><path fill="url(#i21bfyb)" class="tx2om3yfw"/><path fill="url(#iBm9RBb)" class="tx2om3yfw"/><path fill="url(#i0hcINb)" class="tx2om3yfw"/><path fill="url(#iRHzfVd)" class="tx2om3yfw"/><g filter="url(#iwl5Ozb)"><rect fill="url(#i31a57d)" class="zgqyibz6l"/><rect fill="url(#i8d0t8b)" class="zgqyibz6l"/><rect fill="url(#in4IGjc)" class="zgqyibz6l"/></g><rect fill="url(#isMMSdb)" class="ap-god9dl"/><rect fill="url(#idkEA5c)" class="ap-god9dl"/><rect fill="url(#iDlZnPb)" class="ap-god9dl"/><g filter="url(#iokVRWd)"><rect class="hn4geq10y"/></g><g filter="url(#iI9gmve)"><rect class="h3k_uabjy"/></g><rect fill="url(#ivw7Zpe)" class="n9fokxb3a"/><rect fill="url(#ix2sSed)" class="n9fokxb3a"/><rect fill="url(#iuOS7ae)" class="n9fokxb3a"/><defs><radialGradient id="iYETYDy" cx="0" cy="0" r="1" gradientTransform="matrix(8.56555 0 0 4.57895 7.71 11.043)" gradientUnits="userSpaceOnUse"><stop class="gpa94tb4y"/><stop offset="1" class="s6-cyob9e"/></radialGradient><radialGradient id="izPj1Pb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.63519 0 0 -10.3302 16.544 19.184)" gradientUnits="userSpaceOnUse"><stop class="y79h1jb0u"/><stop offset="1" class="df79lkb4g"/></radialGradient><radialGradient id="iHc8ZEd" cx="0" cy="0" r="1" gradientTransform="matrix(4.68782 -7.19713 5.98956 3.90127 15.573 24.596)" gradientUnits="userSpaceOnUse"><stop class="at9977_sk"/><stop offset="1" class="hsmpc6v5e"/></radialGradient><radialGradient id="iEgD3td" cx="0" cy="0" r="1" gradientTransform="matrix(-10.14807 -.05048 .00666 -1.33965 28.08 26.41)" gradientUnits="userSpaceOnUse"><stop class="a5lkoibji"/><stop offset="1" class="sfjtufb3d"/></radialGradient><radialGradient id="iFO5K3d" cx="0" cy="0" r="1" gradientTransform="matrix(4.4375 0 0 4.60372 29.625 27.045)" gradientUnits="userSpaceOnUse"><stop class="a5lkoibji"/><stop offset=".885" class="sfjtufb3d"/></radialGradient><radialGradient id="i21bfyb" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 1.8125 -5.24074 5.42145 12.967 6.38)" gradientUnits="userSpaceOnUse"><stop class="i4b3hhbxu"/><stop offset=".858" class="zdi6vxide"/></radialGradient><radialGradient id="iBm9RBb" cx="0" cy="0" r="1" gradientTransform="rotate(142.344 8.33 7.288)scale(5.01297 1.89469)" gradientUnits="userSpaceOnUse"><stop class="n2lghubug"/><stop offset="1" class="o-9gnobjq"/></radialGradient><radialGradient id="i0hcINb" cx="0" cy="0" r="1" gradientTransform="rotate(129.92 8.932 6.449)scale(2.98951 1.97665)" gradientUnits="userSpaceOnUse"><stop class="dpiwsg14d"/><stop offset="1" class="veug5zb0p"/></radialGradient><radialGradient id="iRHzfVd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53125 0 0 -1.78125 17.752 10.813)" gradientUnits="userSpaceOnUse"><stop class="h8i4c7ili"/><stop offset="1" class="rw48tjbhj"/></radialGradient><radialGradient id="i31a57d" cx="0" cy="0" r="1" gradientTransform="matrix(-7.05928 0 0 -3.41578 23.662 11.85)" gradientUnits="userSpaceOnUse"><stop class="yt0xribym"/><stop offset="1" class="s7-edrslw"/></radialGradient><radialGradient id="in4IGjc" cx="0" cy="0" r="1" gradientTransform="matrix(5.21875 -.25 .16715 3.48919 17.125 15.031)" gradientUnits="userSpaceOnUse"><stop class="lmd-2lf0j"/><stop offset="1" class="bakdbdc-m"/></radialGradient><radialGradient id="isMMSdb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.61788 0 0 -3.37646 22.68 21.615)" gradientUnits="userSpaceOnUse"><stop class="a5lkoibji"/><stop offset="1" class="fg0y7_u_n"/></radialGradient><radialGradient id="iDlZnPb" cx="0" cy="0" r="1" gradientTransform="matrix(7.33922 0 0 2.25494 18.534 25.193)" gradientUnits="userSpaceOnUse"><stop class="nl1n8ormd"/><stop offset="1" class="cfz47hkkg"/></radialGradient><radialGradient id="ivw7Zpe" cx="0" cy="0" r="1" gradientTransform="matrix(-5.50322 .2293 -.11912 -2.8589 22.22 16.4)" gradientUnits="userSpaceOnUse"><stop class="phpmogblj"/><stop offset="1" class="qcayvqx4z"/></radialGradient><radialGradient id="iuOS7ae" cx="0" cy="0" r="1" gradientTransform="matrix(6.46207 0 0 3.4824 17.179 20.162)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="po9rmpbja"/><stop offset="1" class="xvld2motu"/></radialGradient><linearGradient id="iB4lHPc" x1="14.36" x2="30.649" y1="31.333" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="rtuw9rlhz"/><stop offset="1" class="ua9zxdp4p"/></linearGradient><linearGradient id="i7ySpsf" x1="18.395" x2="18.395" y1="34.172" y2="26.547" gradientUnits="userSpaceOnUse"><stop class="aytl0bqim"/><stop offset="1" class="h95nyubdx"/></linearGradient><linearGradient id="i8d0t8b" x1="14.772" x2="19.102" y1="13.293" y2="13.293" gradientUnits="userSpaceOnUse"><stop class="w95eypajp"/><stop offset="1" class="uxl59eiqs"/></linearGradient><linearGradient id="idkEA5c" x1="14.772" x2="19.102" y1="23.107" y2="23.107" gradientUnits="userSpaceOnUse"><stop class="i3484_86c"/><stop offset="1" class="hy2pq4b0i"/></linearGradient><linearGradient id="ix2sSed" x1="15.376" x2="19.102" y1="18.155" y2="18.155" gradientUnits="userSpaceOnUse"><stop class="xaeobzb5i"/><stop offset="1" class="k1ojisfak"/></linearGradient><filter id="i7GsqVd" width="27.371" height="28.636" x="2.689" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.72549 0 0 0 0 0.494118 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2665"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.945098 0 0 0 0 0.713726 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2665" result="effect2_innerShadow_20020_2665"/></filter><filter id="iedevSc" width="11.25" height="16.974" x="13.037" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2665" stdDeviation=".75"/></filter><filter id="iwl5Ozb" width="10.338" height="6.078" x="15.376" y="9.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.854902 0 0 0 0 0.65098 0 0 0 0 0.537255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2665"/></filter><filter id="iokVRWd" width="8.315" height="2.188" x="16.308" y="13.645" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2665" stdDeviation=".375"/></filter><filter id="iI9gmve" width="8.315" height="2.188" x="16.308" y="19.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2665" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:call-me-hand-light" /></template>
<style>
.a5lkoibji {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
}

.ap-god9dl {
  width: 10.088px;
  height: 5.781px;
  x: 15.376px;
  y: 19.412px;
  rx: 2.891px;
}

.at9977_sk {
  stop-color: var(--svg-color--bd7e7f, #BD7E7F);
}

.aytl0bqim {
  stop-color: var(--svg-color--bd8095, #BD8095);
}

.bakdbdc-m {
  stop-color: var(--svg-color--d9a193, #D9A193);
  stop-opacity: 0;
}

.cfz47hkkg {
  stop-color: var(--svg-color--bf8293, #BF8293);
  stop-opacity: 0;
}

.df79lkb4g {
  stop-color: var(--svg-color--d9a494, #D9A494);
  stop-opacity: 0;
}

.dpiwsg14d {
  stop-color: var(--svg-color--ffe6c8, #FFE6C8);
}

.fg0y7_u_n {
  stop-color: var(--svg-color--e4b1a0, #E4B1A0);
}

.ft5dv1b6b {
  fill: none;
}

.gpa94tb4y {
  stop-color: var(--svg-color--f2c1a7, #F2C1A7);
}

.h3k_uabjy {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 19.818px;
  fill: var(--svg-color--d99b7e, #D99B7E);
  rx: 0.344px;
}

.h8i4c7ili {
  stop-color: var(--svg-color--ffcdaf, #FFCDAF);
}

.h95nyubdx {
  stop-color: var(--svg-color--bd8095, #BD8095);
  stop-opacity: 0;
}

.hn4geq10y {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 14.395px;
  fill: var(--svg-color--d99b7e, #D99B7E);
  rx: 0.344px;
}

.hsmpc6v5e {
  stop-color: var(--svg-color--ad705c, #AD705C);
}

.hy2pq4b0i {
  stop-color: var(--svg-color--d29e8d, #D29E8D);
  stop-opacity: 0;
}

.i3484_86c {
  stop-color: var(--svg-color--d29e8d, #D29E8D);
}

.i4b3hhbxu {
  stop-color: var(--svg-color--d9a78b, #D9A78B);
}

.k1ojisfak {
  stop-color: var(--svg-color--d7a28b, #D7A28B);
  stop-opacity: 0;
}

.lmd-2lf0j {
  stop-color: var(--svg-color--d9a193, #D9A193);
}

.n2lghubug {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
}

.n9fokxb3a {
  width: 10.088px;
  height: 5.563px;
  x: 15.376px;
  y: 14.599px;
  rx: 2.781px;
}

.nl1n8ormd {
  stop-color: var(--svg-color--bf8293, #BF8293);
}

.o-9gnobjq {
  stop-color: var(--svg-color--f1bea1, #F1BEA1);
  stop-opacity: 0;
}

.phpmogblj {
  stop-color: var(--svg-color--ffe6cb, #FFE6CB);
}

.po9rmpbja {
  stop-color: var(--svg-color--d49996, #D49996);
}

.qcayvqx4z {
  stop-color: var(--svg-color--eab7a2, #EAB7A2);
}

.qxrjxujji {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  rx: 2.898px;
}

.rtuw9rlhz {
  stop-color: var(--svg-color--e8b3a5, #E8B3A5);
}

.rw48tjbhj {
  stop-color: var(--svg-color--ffcdaf, #FFCDAF);
  stop-opacity: 0;
}

.s6-cyob9e {
  stop-color: var(--svg-color--f2c1a7, #F2C1A7);
  stop-opacity: 0;
}

.s7-edrslw {
  stop-color: var(--svg-color--eebca4, #EEBCA4);
}

.sfjtufb3d {
  stop-color: var(--svg-color--ffe2c8, #FFE2C8);
  stop-opacity: 0;
}

.tx2om3yfw {
  d: path("m17.97 10.425l-.008-.005c.597-.853 1.968-2.82 2.508-3.703c.79-1.29.679-3.1-.581-4.073a2.76 2.76 0 0 0-1.69-.587a3 3 0 0 0-1.566.46c-.36.222-.7.528-1 .918c-2.388 3.7-5.187 5.899-6.611 6.504l-.035.02q-.196.087-.389.182c-.155.108-.203.22-.236.559c-.133 1.348 1.235 3.249 2.294 4.058c1.271.972 3.09.73 4.063-.542l2.967-3.39z");
}

.ua9zxdp4p {
  stop-color: var(--svg-color--fccdb0, #FCCDB0);
}

.ueos9yy2y {
  d: path("M14.537 14.715c0-1.439 1.07-2.606 2.388-2.606H20.4c1.319 0 2.388 1.167 2.388 2.606c0 .942-.457 1.767-1.143 2.224c.683.43 1.143 1.235 1.143 2.157c0 .934-.471 1.747-1.168 2.173c.699.449 1.168 1.28 1.168 2.229c0 .75-.145 1.874-1.338 2.15l-4.543.435c-1.308 0-2.369-1.157-2.369-2.585c0-.95.47-1.78 1.169-2.23c-.697-.425-1.169-1.238-1.169-2.172c0-.922.46-1.727 1.143-2.157c-.685-.457-1.143-1.282-1.143-2.224");
}

.ujydyib8d {
  d: path("M17.962 10.42c3.188 1.826 5.35 5.346 5.35 9.273c0 1.603-.361 3.112-1.004 4.453h4.13c1.587 0 2.873 1.298 2.873 2.899s-1.286 2.898-2.872 2.898H14.084q-.33 0-.634-.008q-.21.008-.419.008c-6.874 0-10.342-4.551-10.342-10.281c0-4.284 2.608-8.067 6.298-9.703l.035-.02c1.424-.605 4.223-2.804 6.61-6.504c1.192-1.547 2.997-1.764 4.257-.791c1.26.972 1.371 2.784.581 4.073c-.54.883-1.911 2.85-2.508 3.703");
}

.uxl59eiqs {
  stop-color: var(--svg-color--dda78d, #DDA78D);
  stop-opacity: 0;
}

.veug5zb0p {
  stop-color: var(--svg-color--ffe6c8, #FFE6C8);
  stop-opacity: 0;
}

.w95eypajp {
  stop-color: var(--svg-color--dda78d, #DDA78D);
}

.xaeobzb5i {
  stop-color: var(--svg-color--d7a28b, #D7A28B);
}

.xvld2motu {
  stop-color: var(--svg-color--d49996, #D49996);
  stop-opacity: 0;
}

.y79h1jb0u {
  stop-color: var(--svg-color--d9a494, #D9A494);
}

.yt0xribym {
  stop-color: var(--svg-color--ffe7ca, #FFE7CA);
}

.zdi6vxide {
  stop-color: var(--svg-color--d9a78b, #D9A78B);
  stop-opacity: 0;
}

.zgqyibz6l {
  width: 10.088px;
  height: 5.828px;
  x: 15.376px;
  y: 9.568px;
  rx: 2.914px;
}

.zys7f72ey {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 2.898px;
}

</style>
