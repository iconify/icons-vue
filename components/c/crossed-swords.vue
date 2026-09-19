<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iwo08lP)" transform="rotate(-45 21.448 23.87)" class="c2ju5za5i"/><g filter="url(#iUm0EgL)"><path fill="url(#iSsiJZc)" transform="rotate(-45 22.436 22.883)" class="rh-xtzgpu"/></g><g filter="url(#ie6H43v)"><path fill="url(#ixZI9rc)" class="jv2pmfptx"/><path fill="url(#ij1uB8c)" class="jv2pmfptx"/><path fill="url(#ibIzl8c)" class="jv2pmfptx"/></g><g filter="url(#i7HQD6d)"><path fill="url(#ifvNjEd)" class="b49-d-b6p"/><path fill="url(#iOzJaqc)" class="b49-d-b6p"/></g><path fill="url(#i4KXNEc)" class="b49-d-b6p"/><g filter="url(#iQLJN7b)"><path fill="url(#iEH0q6c)" class="y57jw3b-x"/><path fill="url(#iMi0nib)" class="y57jw3b-x"/><path fill="url(#iQX7YAE)" class="y57jw3b-x"/><path fill="url(#iIdnR2p)" class="y57jw3b-x"/></g><path class="hlmnmnpae"/><path fill="url(#iy7v2Qc)" class="c1-jrwb0j"/><path fill="url(#iJtup9b)" class="c1-jrwb0j"/><path fill="url(#ilUN1zb)" class="c1-jrwb0j"/><path fill="url(#i6FWTvb)" class="c1-jrwb0j"/><g filter="url(#ia62gfe)"><path fill="url(#idyk0nd)" class="uq-xe36if"/></g><path fill="url(#it1h1je)" transform="scale(-1 1)rotate(-45 24.019 23.511)" class="guyt7l52h"/><g filter="url(#ilYUM7c)"><path fill="url(#iO1DgMb)" transform="scale(-1 1)rotate(-45 23.32 21.826)" class="f4a93baml"/></g><g filter="url(#iZfDYVd)"><path fill="url(#imP6pHb)" class="qiyicdcki"/><path fill="url(#i31brMd)" class="qiyicdcki"/></g><g filter="url(#iSr0Tne)"><path fill="url(#iHdcENb)" class="dymdgps7w"/><path fill="url(#iBu2ztc)" class="dymdgps7w"/></g><path fill="url(#iqkzfrd)" class="dymdgps7w"/><g filter="url(#ivEZeGG)"><path fill="url(#iGa3rMb)" class="ize77pb0y"/><path fill="url(#i1ge8Vc)" class="ize77pb0y"/></g><path class="s69iiub1a"/><path fill="url(#itMt7Eb)" class="u1bf83b3y"/><path fill="url(#iyO8Y4b)" class="u1bf83b3y"/><path fill="url(#iSP8tQd)" class="u1bf83b3y"/><path fill="url(#iEmpJ0b)" class="u1bf83b3y"/><g filter="url(#iVjJqFx)"><path fill="url(#iqPr3Iu)" class="b-opvpbse"/></g><defs><linearGradient id="iwo08lP" x1="22.787" x2="22.668" y1="23.87" y2="29.384" gradientUnits="userSpaceOnUse"><stop class="t_ne_ulco"/><stop offset="1" class="efzwwd9fx"/></linearGradient><linearGradient id="iSsiJZc" x1="22.79" x2="22.79" y1="22.883" y2="29.324" gradientUnits="userSpaceOnUse"><stop class="wfrjveixc"/><stop offset="1" class="s_2knvovs"/></linearGradient><linearGradient id="ixZI9rc" x1="7.147" x2="20.959" y1="9.437" y2="23.719" gradientUnits="userSpaceOnUse"><stop class="j9xg5tb0p"/><stop offset="1" class="lxk8teb2j"/></linearGradient><linearGradient id="ij1uB8c" x1="15.834" x2="13.366" y1="12.625" y2="15.031" gradientUnits="userSpaceOnUse"><stop offset=".478" class="qs2z-ccff"/><stop offset="1" class="x81i2dbzp"/></linearGradient><linearGradient id="ifvNjEd" x1="27.147" x2="27.147" y1="25.656" y2="29.951" gradientUnits="userSpaceOnUse"><stop class="miecs2bxe"/><stop offset="1" class="hz-vm1bdx"/></linearGradient><linearGradient id="iEH0q6c" x1="3.616" x2="22.366" y1="2.719" y2="20.875" gradientUnits="userSpaceOnUse"><stop class="vsejucb1z"/><stop offset="1" class="l470qbb2d"/></linearGradient><linearGradient id="iMi0nib" x1="13.772" x2="14.155" y1="14.516" y2="14.109" gradientUnits="userSpaceOnUse"><stop class="so6qtibvx"/><stop offset="1" class="sdtmkqbwe"/></linearGradient><linearGradient id="iy7v2Qc" x1="16.694" x2="18.959" y1="24.688" y2="24.844" gradientUnits="userSpaceOnUse"><stop offset=".255" class="tct_eccsc"/><stop offset="1" class="na4jhp11e"/></linearGradient><linearGradient id="idyk0nd" x1="23.897" x2="17.428" y1="18.594" y2="25.063" gradientUnits="userSpaceOnUse"><stop class="rx-cfybqr"/><stop offset="1" class="bn9zv2yzi"/></linearGradient><linearGradient id="it1h1je" x1="1.338" x2="1.22" y1="0" y2="5.513" gradientUnits="userSpaceOnUse"><stop class="t_ne_ulco"/><stop offset="1" class="efzwwd9fx"/></linearGradient><linearGradient id="iO1DgMb" x1=".354" x2=".354" y1="0" y2="6.441" gradientUnits="userSpaceOnUse"><stop class="wfrjveixc"/><stop offset="1" class="s_2knvovs"/></linearGradient><linearGradient id="imP6pHb" x1="23.892" x2="10.079" y1="9.437" y2="23.719" gradientUnits="userSpaceOnUse"><stop class="j9xg5tb0p"/><stop offset="1" class="lxk8teb2j"/></linearGradient><linearGradient id="i31brMd" x1="15.204" x2="17.673" y1="12.625" y2="15.031" gradientUnits="userSpaceOnUse"><stop offset=".478" class="qs2z-ccff"/><stop offset="1" class="x81i2dbzp"/></linearGradient><linearGradient id="iHdcENb" x1="3.892" x2="3.892" y1="25.656" y2="29.951" gradientUnits="userSpaceOnUse"><stop class="miecs2bxe"/><stop offset="1" class="hz-vm1bdx"/></linearGradient><linearGradient id="iGa3rMb" x1="27.423" x2="8.673" y1="2.719" y2="20.875" gradientUnits="userSpaceOnUse"><stop class="vsejucb1z"/><stop offset="1" class="l470qbb2d"/></linearGradient><linearGradient id="i1ge8Vc" x1="17.267" x2="16.884" y1="14.516" y2="14.109" gradientUnits="userSpaceOnUse"><stop class="so6qtibvx"/><stop offset="1" class="sdtmkqbwe"/></linearGradient><linearGradient id="itMt7Eb" x1="14.345" x2="12.079" y1="24.688" y2="24.844" gradientUnits="userSpaceOnUse"><stop offset=".255" class="tct_eccsc"/><stop offset="1" class="na4jhp11e"/></linearGradient><linearGradient id="iqPr3Iu" x1="7.142" x2="13.611" y1="18.594" y2="25.063" gradientUnits="userSpaceOnUse"><stop class="rx-cfybqr"/><stop offset="1" class="bn9zv2yzi"/></linearGradient><radialGradient id="ibIzl8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 1.46875 -5.46005 5.57623 15.7 18.125)" gradientUnits="userSpaceOnUse"><stop offset=".348" class="ixtahxzry"/><stop offset="1" class="c8a0pnbxb"/></radialGradient><radialGradient id="iOzJaqc" cx="0" cy="0" r="1" gradientTransform="rotate(135 8.964 19.181)scale(3.0494 .66291)" gradientUnits="userSpaceOnUse"><stop class="pg67x2uth"/><stop offset="1" class="g0lipybfy"/></radialGradient><radialGradient id="i4KXNEc" cx="0" cy="0" r="1" gradientTransform="rotate(178.44 14.075 14.436)scale(4.01711 4.32354)" gradientUnits="userSpaceOnUse"><stop offset=".695" class="ptcoz3b0o"/><stop offset=".92" class="srq755ssg"/></radialGradient><radialGradient id="iQX7YAE" cx="0" cy="0" r="1" gradientTransform="matrix(2.875 -6.125 2.47822 1.16325 15.2 14.063)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="y5arfybiy"/><stop offset="1" class="foghu78uu"/></radialGradient><radialGradient id="iIdnR2p" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18751 -3.06249 3.78735 -3.94196 23.168 20)" gradientUnits="userSpaceOnUse"><stop offset=".126" class="x_ocqac9n"/><stop offset="1" class="q63b76bcm"/></radialGradient><radialGradient id="iJtup9b" cx="0" cy="0" r="1" gradientTransform="rotate(45.83 -14.54 34.452)scale(3.04972 11.7745)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="z4rhkvyix"/><stop offset=".819" class="l8k4hrbce"/></radialGradient><radialGradient id="ilUN1zb" cx="0" cy="0" r="1" gradientTransform="matrix(2.46875 3.5 -6.0614 4.27545 20.772 20.563)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="firayy89s"/><stop offset=".918" class="p5u8heblq"/></radialGradient><radialGradient id="i6FWTvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1 5.875 -1.17474 -.19996 25.584 17.281)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="iocyusbmx"/><stop offset="1" class="ww6zt341o"/></radialGradient><radialGradient id="iBu2ztc" cx="0" cy="0" r="1" gradientTransform="rotate(45 -30.789 15.826)scale(3.0494 .66291)" gradientUnits="userSpaceOnUse"><stop class="pg67x2uth"/><stop offset="1" class="g0lipybfy"/></radialGradient><radialGradient id="iqkzfrd" cx="0" cy="0" r="1" gradientTransform="matrix(4.01562 .10937 -.11772 4.32194 2.501 28.484)" gradientUnits="userSpaceOnUse"><stop offset=".695" class="ptcoz3b0o"/><stop offset=".92" class="srq755ssg"/></radialGradient><radialGradient id="iyO8Y4b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.12501 2.18749 -8.44556 -8.20435 10.736 20.875)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="z4rhkvyix"/><stop offset=".819" class="l8k4hrbce"/></radialGradient><radialGradient id="iSP8tQd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46878 3.49997 -6.06135 -4.2755 10.267 20.563)" gradientUnits="userSpaceOnUse"><stop offset=".696" class="firayy89s"/><stop offset=".918" class="p5u8heblq"/></radialGradient><radialGradient id="iEmpJ0b" cx="0" cy="0" r="1" gradientTransform="matrix(1 5.875 -1.17474 .19996 5.454 17.281)" gradientUnits="userSpaceOnUse"><stop offset=".095" class="iocyusbmx"/><stop offset="1" class="ww6zt341o"/></radialGradient><filter id="iUm0EgL" width="6.355" height="6.355" x="21.786" y="21.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24030" stdDeviation=".325"/></filter><filter id="ie6H43v" width="22.875" height="22.875" x="1.616" y="2.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.643137 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24030"/></filter><filter id="i7HQD6d" width="4.551" height="4.551" x="24.871" y="25.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.258824 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24030"/></filter><filter id="iQLJN7b" width="22.508" height="20.922" x="1.783" y="2.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.772549 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24030"/></filter><filter id="ia62gfe" width="8.647" height="8.57" x="16.694" y="17.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24030" stdDeviation=".3"/></filter><filter id="ilYUM7c" width="6.355" height="6.355" x="2.898" y="21.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24030" stdDeviation=".325"/></filter><filter id="iZfDYVd" width="22.875" height="22.875" x="6.747" y="2.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.662745 0 0 0 0 0.643137 0 0 0 0 0.686275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24030"/></filter><filter id="iSr0Tne" width="4.551" height="4.551" x="1.616" y="25.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.258824 0 0 0 0 0.552941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24030"/></filter><filter id="ivEZeGG" width="22.508" height="20.922" x="6.747" y="2.106" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.772549 0 0 0 0 0.772549 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24030"/></filter><filter id="iVjJqFx" width="8.647" height="8.57" x="5.698" y="17.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24030" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:crossed-swords" /></template>
<style>
.b-opvpbse {
  d: path("M12.853 25.25q.454 0 .892-.06v-1.518a5.055 5.055 0 0 1-5.881-5.791H6.347q-.05.4-.05.815a6.555 6.555 0 0 0 6.555 6.555");
}

.b49-d-b6p {
  d: path("M25.262 29.56a1.334 1.334 0 0 1 0-1.886l1.883-1.883a1.334 1.334 0 1 1 1.887 1.887l-1.883 1.883a1.334 1.334 0 0 1-1.887 0");
}

.bn9zv2yzi {
  stop-color: var(--svg-color--52475f, #52475F);
}

.c1-jrwb0j {
  d: path("M16.694 25.452c0 .142.099.265.238.29q.611.108 1.254.109a7.155 7.155 0 0 0 7.059-8.328a.29.29 0 0 0-.29-.242h-2.127c-.205 0-.35.202-.303.401q.115.49.116 1.014a4.455 4.455 0 0 1-5.54 4.322c-.202-.05-.407.095-.407.302z");
}

.c2ju5za5i {
  d: path("M21.448 23.87h2.677v6.441h-2.677z");
}

.c8a0pnbxb {
  stop-color: var(--svg-color--8d72a7, #8D72A7);
  stop-opacity: 0;
}

.dymdgps7w {
  d: path("M5.777 29.56a1.334 1.334 0 0 0 0-1.886L3.894 25.79a1.334 1.334 0 0 0-1.887 1.887L3.89 29.56a1.334 1.334 0 0 0 1.887 0");
}

.efzwwd9fx {
  stop-color: var(--svg-color--502e76, #502E76);
}

.f4a93baml {
  d: path("M0 0h.707v6.441H0z");
}

.firayy89s {
  stop-color: var(--svg-color--492e62, #492E62);
  stop-opacity: 0;
}

.foghu78uu {
  stop-color: var(--svg-color--bdb8c2, #BDB8C2);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0lipybfy {
  stop-color: var(--svg-color--736db2, #736DB2);
  stop-opacity: 0;
}

.guyt7l52h {
  d: path("M0 0h2.677v6.441H0z");
}

.hlmnmnpae {
  fill: var(--svg-color--614b76, #614B76);
  d: path("M16.694 25.452c0 .142.099.265.238.29q.611.108 1.254.109a7.155 7.155 0 0 0 7.059-8.328a.29.29 0 0 0-.29-.242h-2.127c-.205 0-.35.202-.303.401q.115.49.116 1.014a4.455 4.455 0 0 1-5.54 4.322c-.202-.05-.407.095-.407.302z");
}

.hz-vm1bdx {
  stop-color: var(--svg-color--6345a1, #6345A1);
}

.iocyusbmx {
  stop-color: var(--svg-color--7a678f, #7A678F);
}

.ixtahxzry {
  stop-color: var(--svg-color--8d72a7, #8D72A7);
}

.ize77pb0y {
  d: path("M29.255 2.293a.6.6 0 0 0-.433-.186h-2.496a2 2 0 0 0-1.415.585L6.747 20.855l1.973 1.973z");
}

.j9xg5tb0p {
  stop-color: var(--svg-color--9f94ac, #9F94AC);
}

.jv2pmfptx {
  d: path("M2.202 6.618a2 2 0 0 1-.586-1.415l.001-2.496a.6.6 0 0 1 .6-.6h2.496a2 2 0 0 1 1.415.585L24.29 20.855l-3.925 3.926z");
}

.l470qbb2d {
  stop-color: var(--svg-color--d7d1de, #D7D1DE);
}

.l8k4hrbce {
  stop-color: var(--svg-color--493a5a, #493A5A);
  stop-opacity: 0;
}

.lxk8teb2j {
  stop-color: var(--svg-color--8f76a7, #8F76A7);
}

.miecs2bxe {
  stop-color: var(--svg-color--6563a7, #6563A7);
}

.na4jhp11e {
  stop-color: var(--svg-color--403848, #403848);
  stop-opacity: 0;
}

.p5u8heblq {
  stop-color: var(--svg-color--492e62, #492E62);
}

.pg67x2uth {
  stop-color: var(--svg-color--736db2, #736DB2);
}

.ptcoz3b0o {
  stop-color: var(--svg-color--6b669f, #6B669F);
  stop-opacity: 0;
}

.q63b76bcm {
  stop-color: var(--svg-color--d1cbd8, #D1CBD8);
  stop-opacity: 0;
}

.qiyicdcki {
  d: path("M28.837 6.618a2 2 0 0 0 .585-1.415V2.707a.6.6 0 0 0-.6-.6h-2.496a2 2 0 0 0-1.415.585L6.747 20.855l3.926 3.926z");
}

.qs2z-ccff {
  stop-color: var(--svg-color--aca0b9, #ACA0B9);
}

.rh-xtzgpu {
  d: path("M22.436 22.883h.707v6.441h-.707z");
}

.rx-cfybqr {
  stop-color: var(--svg-color--654e7e, #654E7E);
}

.s_2knvovs {
  stop-color: var(--svg-color--674d82, #674D82);
}

.s69iiub1a {
  fill: var(--svg-color--614b76, #614B76);
  d: path("M14.345 25.452a.29.29 0 0 1-.239.29q-.611.108-1.253.109a7.155 7.155 0 0 1-7.06-8.328a.29.29 0 0 1 .29-.242h2.128c.204 0 .35.202.303.401a4.455 4.455 0 0 0 5.424 5.336c.201-.05.407.095.407.302z");
}

.sdtmkqbwe {
  stop-color: var(--svg-color--c8bfd2, #C8BFD2);
  stop-opacity: 0;
}

.so6qtibvx {
  stop-color: var(--svg-color--c8bfd2, #C8BFD2);
}

.srq755ssg {
  stop-color: var(--svg-color--6b669f, #6B669F);
}

.t_ne_ulco {
  stop-color: var(--svg-color--2b1e38, #2B1E38);
}

.tct_eccsc {
  stop-color: var(--svg-color--403848, #403848);
}

.u1bf83b3y {
  d: path("M14.345 25.452a.29.29 0 0 1-.239.29q-.611.108-1.253.109a7.155 7.155 0 0 1-7.06-8.328a.29.29 0 0 1 .29-.242h2.128c.204 0 .35.202.303.401a4.455 4.455 0 0 0 5.424 5.336c.201-.05.407.095.407.302z");
}

.uq-xe36if {
  d: path("M18.186 25.25q-.454 0-.892-.06v-1.518q.435.079.892.079a5.055 5.055 0 0 0 4.99-5.87h1.515q.05.4.05.815a6.555 6.555 0 0 1-6.555 6.555");
}

.vsejucb1z {
  stop-color: var(--svg-color--dbd7e0, #DBD7E0);
}

.wfrjveixc {
  stop-color: var(--svg-color--454249, #454249);
}

.ww6zt341o {
  stop-color: var(--svg-color--7a678f, #7A678F);
  stop-opacity: 0;
}

.x_ocqac9n {
  stop-color: var(--svg-color--8a8094, #8A8094);
}

.x81i2dbzp {
  stop-color: var(--svg-color--aca0b9, #ACA0B9);
  stop-opacity: 0;
}

.y57jw3b-x {
  d: path("M1.783 2.293a.6.6 0 0 1 .434-.186h2.496a2 2 0 0 1 1.415.585L24.29 20.855l-1.972 1.973z");
}

.y5arfybiy {
  stop-color: var(--svg-color--bdb8c2, #BDB8C2);
}

.z4rhkvyix {
  stop-color: var(--svg-color--493a5a, #493A5A);
}

</style>
