<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g filter="url(#ioyPTnb)"><path class="qqv33fzeo"/></g><path fill="url(#igm3epH)" class="osiz25byo"/><path fill="url(#if8qknc)" class="osiz25byo"/><path fill="url(#iilwavc)" class="osiz25byo"/><path fill="url(#iyqfgVd)" class="osiz25byo"/><path fill="url(#iVPMcbb)" class="osiz25byo"/><g filter="url(#i5WXxKe)"><rect stroke="url(#irV9Rwe)" transform="rotate(45 23.026 .843)" class="rc4oq8jjm"/><rect stroke="url(#iu38wJd)" transform="rotate(45 23.026 .843)" class="rc4oq8jjm"/></g><g filter="url(#i9Xppkc)"><path class="xt2inu43w"/></g><path fill="url(#iqS22Cb)" class="njnpabciz"/><path fill="url(#iHQZrae)" class="njnpabciz"/><path fill="url(#iZNwFTb)" class="njnpabciz"/><path fill="url(#i5BoUGb)" class="njnpabciz"/><path fill="url(#i8iKOeV)" class="njnpabciz"/><g filter="url(#idHy1Xd)"><rect stroke="url(#iSZ6Pab)" transform="rotate(45 14.747 8.834)" class="emjyzlbbi"/><rect stroke="url(#iAyob9b)" transform="rotate(45 14.747 8.834)" class="emjyzlbbi"/></g></g><defs><radialGradient id="igm3epH" cx="0" cy="0" r="1" gradientTransform="rotate(89.324 5.023 14.359)scale(13.7774 14.0197)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="t5ns044ka"/><stop offset=".969" class="jjwgwibhe"/></radialGradient><radialGradient id="if8qknc" cx="0" cy="0" r="1" gradientTransform="matrix(.8534 -2.51958 7.13302 2.41602 14.566 10.793)" gradientUnits="userSpaceOnUse"><stop class="dxt3ii92y"/><stop offset="1" class="myvnh3bfk"/></radialGradient><radialGradient id="iyqfgVd" cx="0" cy="0" r="1" gradientTransform="matrix(.81277 -3.82 4.9334 1.04966 23.385 7.867)" gradientUnits="userSpaceOnUse"><stop class="v49pbpbbt"/><stop offset="1" class="lw7-dlpku"/></radialGradient><radialGradient id="iVPMcbb" cx="0" cy="0" r="1" gradientTransform="matrix(.8534 2.51958 -6.41684 2.17344 12.087 14.044)" gradientUnits="userSpaceOnUse"><stop offset=".161" class="wk-3_omaa"/><stop offset="1" class="zlxf9gb1k"/></radialGradient><radialGradient id="iqS22Cb" cx="0" cy="0" r="1" gradientTransform="rotate(89.324 -3.05 14.286)scale(13.7774 14.0197)" gradientUnits="userSpaceOnUse"><stop offset=".774" class="t5ns044ka"/><stop offset=".969" class="jjwgwibhe"/></radialGradient><radialGradient id="iHQZrae" cx="0" cy="0" r="1" gradientTransform="matrix(.8534 -2.51958 7.13302 2.41602 6.517 18.793)" gradientUnits="userSpaceOnUse"><stop class="dxt3ii92y"/><stop offset="1" class="myvnh3bfk"/></radialGradient><radialGradient id="i5BoUGb" cx="0" cy="0" r="1" gradientTransform="matrix(.81277 -3.82 4.9334 1.04966 15.336 15.867)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="v49pbpbbt"/><stop offset="1" class="lw7-dlpku"/></radialGradient><radialGradient id="i8iKOeV" cx="0" cy="0" r="1" gradientTransform="matrix(-4.8156 3.92164 -2.28327 -2.80376 21.515 19.042)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="d5i2t_bxt"/><stop offset="1" class="sys3b1x6m"/></radialGradient><linearGradient id="iilwavc" x1="12.25" x2="13.753" y1="8.395" y2="9.939" gradientUnits="userSpaceOnUse"><stop offset=".299" class="oetw53b6e"/><stop offset="1" class="v-qo369no"/></linearGradient><linearGradient id="irV9Rwe" x1="34.798" x2="30.376" y1="-1.087" y2="6.689" gradientUnits="userSpaceOnUse"><stop offset=".272" class="kzp7be8ci"/><stop offset="1" class="fkp6f1uxd"/></linearGradient><linearGradient id="iu38wJd" x1="23.332" x2="27.87" y1="17.079" y2="14.58" gradientUnits="userSpaceOnUse"><stop offset=".143" class="v6v18m2rm"/><stop offset="1" class="fkp6f1uxd"/><stop offset="1" class="qxqyb5biz"/></linearGradient><linearGradient id="iZNwFTb" x1="4.201" x2="5.705" y1="16.395" y2="17.939" gradientUnits="userSpaceOnUse"><stop class="oetw53b6e"/><stop offset="1" class="v-qo369no"/></linearGradient><linearGradient id="iSZ6Pab" x1="18.677" x2="21.719" y1="7.247" y2="14.473" gradientUnits="userSpaceOnUse"><stop class="kzp7be8ci"/><stop offset="1" class="fkp6f1uxd"/></linearGradient><linearGradient id="iAyob9b" x1="21.924" x2="19.812" y1="26.752" y2="21.97" gradientUnits="userSpaceOnUse"><stop offset=".143" class="ejjj73bvm"/><stop offset="1" class="fkp6f1uxd"/><stop offset="1" class="hax9_ibig"/></linearGradient><filter id="ioyPTnb" width="20.204" height="20.315" x="10.835" y="1.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.588235 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24636"/></filter><filter id="i5WXxKe" width="20.147" height="20.147" x="10.85" y="1.847" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24636" stdDeviation=".5"/></filter><filter id="i9Xppkc" width="20.204" height="20.315" x="2.786" y="9.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65" dy="-.65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.65098 0 0 0 0 0.588235 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_24636"/></filter><filter id="idHy1Xd" width="19.599" height="19.599" x="3.119" y="9.837" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_24636" stdDeviation=".5"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:link" /></template>
<style>
.d5i2t_bxt {
  stop-color: var(--svg-color--92889c, #92889C);
}

.dxt3ii92y {
  stop-color: var(--svg-color--cdc4d3, #CDC4D3);
}

.ejjj73bvm {
  stop-color: var(--svg-color--e3d8ea, #E3D8EA);
}

.emjyzlbbi {
  width: 12.691px;
  height: 17.864px;
  x: 14.747px;
  y: 8.834px;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  rx: 6.345px;
}

.fkp6f1uxd {
  stop-color: var(--svg-color--f1e9f5, #F1E9F5);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hax9_ibig {
  stop-color: var(--svg-color--e3d8ea, #E3D8EA);
  stop-opacity: 0;
}

.jjwgwibhe {
  stop-color: var(--svg-color--8c72a5, #8C72A5);
}

.kzp7be8ci {
  stop-color: var(--svg-color--f1e9f5, #F1E9F5);
}

.lw7-dlpku {
  stop-color: var(--svg-color--ab9fb5, #AB9FB5);
  stop-opacity: 0;
}

.myvnh3bfk {
  stop-color: var(--svg-color--cdc4d3, #CDC4D3);
  stop-opacity: 0;
}

.njnpabciz {
  d: path("M15.859 10.253a7.77 7.77 0 0 1 4.307 2.192a7.77 7.77 0 0 1 2.174 4.2l-.597.597a4.53 4.53 0 0 1-2.577 1.287a4.54 4.54 0 0 0-1.298-3.786a4.54 4.54 0 0 0-3.859-1.288a4.53 4.53 0 0 0-2.577 1.288l-4.063 4.062a4.551 4.551 0 0 0 6.437 6.437l3.51-3.511a7.8 7.8 0 0 0 4.473-.62a7.8 7.8 0 0 1-1.623 2.366l-4.062 4.063A7.801 7.801 0 0 1 5.07 16.507l4.063-4.062a7.79 7.79 0 0 1 6.725-2.192");
}

.oetw53b6e {
  stop-color: var(--svg-color--ded6e0, #DED6E0);
}

.osiz25byo {
  d: path("M28.104 4.445a7.8 7.8 0 0 0-11.033 0L13.01 8.507a7.8 7.8 0 0 0-1.623 2.366a7.8 7.8 0 0 1 4.473-.62l3.51-3.51a4.551 4.551 0 1 1 6.437 6.436l-4.063 4.063a4.551 4.551 0 0 1-7.734-3.787a4.53 4.53 0 0 0-2.577 1.288l-.597.597a7.801 7.801 0 0 0 13.206 4.2l4.063-4.063a7.8 7.8 0 0 0 0-11.032");
}

.qqv33fzeo {
  fill: var(--svg-color--c8bdcd, #C8BDCD);
  d: path("M28.104 4.445a7.8 7.8 0 0 0-11.033 0L13.01 8.507a7.8 7.8 0 0 0-1.623 2.366a7.8 7.8 0 0 1 4.473-.62l3.51-3.51a4.551 4.551 0 1 1 6.437 6.436l-4.063 4.063a4.551 4.551 0 0 1-7.734-3.787a4.53 4.53 0 0 0-2.577 1.288l-.597.597a7.801 7.801 0 0 0 13.206 4.2l4.063-4.063a7.8 7.8 0 0 0 0-11.032");
}

.qxqyb5biz {
  stop-color: var(--svg-color--c9bdd2, #C9BDD2);
  stop-opacity: 0;
}

.rc4oq8jjm {
  width: 12.691px;
  height: 18.639px;
  x: 23.026px;
  y: 0.843px;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  rx: 6.345px;
}

.sys3b1x6m {
  stop-color: var(--svg-color--92889c, #92889C);
  stop-opacity: 0;
}

.t5ns044ka {
  stop-color: var(--svg-color--a08faf, #A08FAF);
  stop-opacity: 0;
}

.v-qo369no {
  stop-color: var(--svg-color--ded6e0, #DED6E0);
  stop-opacity: 0;
}

.v49pbpbbt {
  stop-color: var(--svg-color--9378a9, #9378A9);
}

.v6v18m2rm {
  stop-color: var(--svg-color--c9bdd2, #C9BDD2);
}

.wk-3_omaa {
  stop-color: var(--svg-color--9789a3, #9789A3);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xt2inu43w {
  fill: var(--svg-color--c8bdcd, #C8BDCD);
  d: path("M15.859 10.253a7.77 7.77 0 0 1 4.307 2.192a7.77 7.77 0 0 1 2.174 4.2l-.597.597a4.53 4.53 0 0 1-2.577 1.287a4.54 4.54 0 0 0-1.298-3.786a4.54 4.54 0 0 0-3.859-1.288a4.53 4.53 0 0 0-2.577 1.288l-4.063 4.062a4.551 4.551 0 0 0 6.437 6.437l3.51-3.511a7.8 7.8 0 0 0 4.473-.62a7.8 7.8 0 0 1-1.623 2.366l-4.062 4.063A7.801 7.801 0 0 1 5.07 16.507l4.063-4.062a7.79 7.79 0 0 1 6.725-2.192");
}

.zlxf9gb1k {
  stop-color: var(--svg-color--9789a3, #9789A3);
  stop-opacity: 0;
}

</style>
