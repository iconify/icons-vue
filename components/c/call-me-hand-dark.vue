<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i2eI8cc)"><path fill="url(#iZDFqze)" class="ujydyib8d"/><path fill="url(#ieTVOXZ)" class="ujydyib8d"/><path fill="url(#iWqwYju)" class="ujydyib8d"/><path fill="url(#iHe1H2c)" class="ujydyib8d"/></g><g filter="url(#iBxFsAc)"><path fill="url(#iHw3hsR)" class="ueos9yy2y"/></g><rect fill="url(#ijdiave)" class="zys7f72ey"/><rect fill="url(#iQFWMId)" class="qxrjxujji"/><path fill="url(#iT8H2od)" class="tx2om3yfw"/><path fill="url(#iOCxTJd)" class="tx2om3yfw"/><path fill="url(#iRyrcXC)" class="tx2om3yfw"/><path fill="url(#ifM20he)" class="tx2om3yfw"/><rect fill="url(#iKTfNmd)" class="zgqyibz6l"/><rect fill="url(#iNXFv3d)" class="zgqyibz6l"/><rect fill="url(#i2lbVte)" class="ap-god9dl"/><rect fill="url(#ioqtiOD)" class="ap-god9dl"/><rect fill="url(#iSQpcme)" class="ap-god9dl"/><g filter="url(#idjFg0c)"><rect class="fna2tp2ed"/></g><g filter="url(#idRva8d)"><rect class="lm7lry1ov"/></g><rect fill="url(#iGcKCce)" class="n9fokxb3a"/><rect fill="url(#ibeqHIc)" class="n9fokxb3a"/><rect fill="url(#ihhw9sc)" class="n9fokxb3a"/><defs><radialGradient id="ieTVOXZ" cx="0" cy="0" r="1" gradientTransform="matrix(8.56555 0 0 4.57895 7.71 11.043)" gradientUnits="userSpaceOnUse"><stop class="y0afrubvw"/><stop offset="1" class="ushh2_8bd"/></radialGradient><radialGradient id="iHe1H2c" cx="0" cy="0" r="1" gradientTransform="matrix(-6.63519 0 0 -10.3302 16.544 19.184)" gradientUnits="userSpaceOnUse"><stop class="iswvkbcho"/><stop offset="1" class="chvhz46vi"/></radialGradient><radialGradient id="iHw3hsR" cx="0" cy="0" r="1" gradientTransform="matrix(4.68782 -7.19713 5.98956 3.90127 15.573 24.596)" gradientUnits="userSpaceOnUse"><stop class="emfwsoy6r"/><stop offset="1" class="uyg-dupgi"/></radialGradient><radialGradient id="ijdiave" cx="0" cy="0" r="1" gradientTransform="matrix(-10.14807 -.05048 .00666 -1.33965 28.08 26.41)" gradientUnits="userSpaceOnUse"><stop class="rg3n2_b4b"/><stop offset="1" class="dxyp9sb9a"/></radialGradient><radialGradient id="iQFWMId" cx="0" cy="0" r="1" gradientTransform="rotate(-42.93 47.206 -22.411)scale(2.54081 2.06084)" gradientUnits="userSpaceOnUse"><stop class="rg3n2_b4b"/><stop offset="1" class="dxyp9sb9a"/></radialGradient><radialGradient id="iT8H2od" cx="0" cy="0" r="1" gradientTransform="matrix(1.875 1.8125 -5.24074 5.42145 12.967 6.38)" gradientUnits="userSpaceOnUse"><stop class="gvfsoebsi"/><stop offset=".858" class="gpjikkbei"/></radialGradient><radialGradient id="iOCxTJd" cx="0" cy="0" r="1" gradientTransform="rotate(129.92 8.932 6.449)scale(2.98951 1.97665)" gradientUnits="userSpaceOnUse"><stop class="xm34y9b_d"/><stop offset="1" class="iv6sy1bym"/></radialGradient><radialGradient id="iRyrcXC" cx="0" cy="0" r="1" gradientTransform="rotate(142.344 8.33 7.288)scale(5.01297 1.89469)" gradientUnits="userSpaceOnUse"><stop class="bm3pv8bcl"/><stop offset="1" class="n9b41vuei"/></radialGradient><radialGradient id="ifM20he" cx="0" cy="0" r="1" gradientTransform="matrix(-3.53125 0 0 -1.78125 17.752 10.813)" gradientUnits="userSpaceOnUse"><stop class="zfrtjb4gd"/><stop offset="1" class="ixtrpihsf"/></radialGradient><radialGradient id="iKTfNmd" cx="0" cy="0" r="1" gradientTransform="matrix(-5.875 0 0 -2.84274 23.662 11.85)" gradientUnits="userSpaceOnUse"><stop class="eser-fblc"/><stop offset="1" class="jji4ghbxr"/></radialGradient><radialGradient id="i2lbVte" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.20272 22.19 21.615)" gradientUnits="userSpaceOnUse"><stop class="eser-fblc"/><stop offset="1" class="jji4ghbxr"/></radialGradient><radialGradient id="iSQpcme" cx="0" cy="0" r="1" gradientTransform="matrix(5.90625 0 0 2.63668 17.033 23.875)" gradientUnits="userSpaceOnUse"><stop class="uzwc_ugjd"/><stop offset="1" class="gdl7jobef"/></radialGradient><radialGradient id="iGcKCce" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65625 0 0 -2.11937 22.19 16.719)" gradientUnits="userSpaceOnUse"><stop class="eser-fblc"/><stop offset="1" class="jji4ghbxr"/></radialGradient><radialGradient id="ihhw9sc" cx="0" cy="0" r="1" gradientTransform="matrix(5.65625 0 0 2.42953 16.564 19.313)" gradientUnits="userSpaceOnUse"><stop class="uzwc_ugjd"/><stop offset="1" class="gdl7jobef"/></radialGradient><linearGradient id="iZDFqze" x1="14.36" x2="30.649" y1="31.333" y2="11.98" gradientUnits="userSpaceOnUse"><stop class="euv_c6bft"/><stop offset="1" class="z_9l1gcue"/></linearGradient><linearGradient id="iWqwYju" x1="18.212" x2="18.212" y1="30.189" y2="26.494" gradientUnits="userSpaceOnUse"><stop class="uo58ai19j"/><stop offset="1" class="gz90bxbvg"/></linearGradient><linearGradient id="iNXFv3d" x1="14.772" x2="19.102" y1="13.293" y2="13.293" gradientUnits="userSpaceOnUse"><stop class="wn-9kxdtp"/><stop offset="1" class="k32f8nbsx"/></linearGradient><linearGradient id="ioqtiOD" x1="14.772" x2="19.102" y1="23.107" y2="23.107" gradientUnits="userSpaceOnUse"><stop class="wn-9kxdtp"/><stop offset="1" class="k32f8nbsx"/></linearGradient><linearGradient id="ibeqHIc" x1="14.772" x2="19.102" y1="18.155" y2="18.155" gradientUnits="userSpaceOnUse"><stop class="wn-9kxdtp"/><stop offset="1" class="k32f8nbsx"/></linearGradient><filter id="i2eI8cc" width="27.371" height="28.636" x="2.689" y="1.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.129412 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_2625"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_2625" result="effect2_innerShadow_20020_2625"/></filter><filter id="iBxFsAc" width="11.25" height="16.974" x="13.037" y="10.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2625" stdDeviation=".75"/></filter><filter id="idjFg0c" width="8.315" height="2.188" x="16.308" y="13.506" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2625" stdDeviation=".375"/></filter><filter id="idRva8d" width="8.315" height="2.188" x="16.308" y="19.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_2625" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:call-me-hand-dark" /></template>
<style>
.ap-god9dl {
  width: 10.088px;
  height: 5.781px;
  x: 15.376px;
  y: 19.412px;
  rx: 2.891px;
}

.bm3pv8bcl {
  stop-color: var(--svg-color--3c201b, #3C201B);
}

.chvhz46vi {
  stop-color: var(--svg-color--402f30, #402F30);
  stop-opacity: 0;
}

.dxyp9sb9a {
  stop-color: var(--svg-color--665150, #665150);
  stop-opacity: 0;
}

.emfwsoy6r {
  stop-color: var(--svg-color--2f1a24, #2F1A24);
}

.eser-fblc {
  stop-color: var(--svg-color--675250, #675250);
}

.euv_c6bft {
  stop-color: var(--svg-color--442c2d, #442C2D);
}

.fna2tp2ed {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 14.256px;
  fill: var(--svg-color--2d1c1a, #2D1C1A);
  rx: 0.344px;
}

.ft5dv1b6b {
  fill: none;
}

.gdl7jobef {
  stop-color: var(--svg-color--3d222e, #3D222E);
  stop-opacity: 0;
}

.gpjikkbei {
  stop-color: var(--svg-color--463938, #463938);
  stop-opacity: 0;
}

.gvfsoebsi {
  stop-color: var(--svg-color--463938, #463938);
}

.gz90bxbvg {
  stop-color: var(--svg-color--402332, #402332);
  stop-opacity: 0;
}

.iswvkbcho {
  stop-color: var(--svg-color--402f30, #402F30);
}

.iv6sy1bym {
  stop-color: var(--svg-color--65514f, #65514F);
  stop-opacity: 0;
}

.ixtrpihsf {
  stop-color: var(--svg-color--594744, #594744);
  stop-opacity: 0;
}

.jji4ghbxr {
  stop-color: var(--svg-color--3f2b29, #3F2B29);
}

.k32f8nbsx {
  stop-color: var(--svg-color--3f2a29, #3F2A29);
  stop-opacity: 0;
}

.lm7lry1ov {
  width: 6.815px;
  height: 0.688px;
  x: 17.058px;
  y: 19.818px;
  fill: var(--svg-color--2d1c1a, #2D1C1A);
  rx: 0.344px;
}

.n9b41vuei {
  stop-color: var(--svg-color--3c201b, #3C201B);
  stop-opacity: 0;
}

.n9fokxb3a {
  width: 10.088px;
  height: 5.563px;
  x: 15.376px;
  y: 14.599px;
  rx: 2.781px;
}

.qxrjxujji {
  width: 15.25px;
  height: 5.797px;
  x: 14.06px;
  y: 24.146px;
  rx: 2.898px;
}

.rg3n2_b4b {
  stop-color: var(--svg-color--665150, #665150);
}

.tx2om3yfw {
  d: path("m17.97 10.425l-.008-.005c.597-.853 1.968-2.82 2.508-3.703c.79-1.29.679-3.1-.581-4.073a2.76 2.76 0 0 0-1.69-.587a3 3 0 0 0-1.566.46c-.36.222-.7.528-1 .918c-2.388 3.7-5.187 5.899-6.611 6.504l-.035.02q-.196.087-.389.182c-.155.108-.203.22-.236.559c-.133 1.348 1.235 3.249 2.294 4.058c1.271.972 3.09.73 4.063-.542l2.967-3.39z");
}

.ueos9yy2y {
  d: path("M14.537 14.715c0-1.439 1.07-2.606 2.388-2.606H20.4c1.319 0 2.388 1.167 2.388 2.606c0 .942-.457 1.767-1.143 2.224c.683.43 1.143 1.235 1.143 2.157c0 .934-.471 1.747-1.168 2.173c.699.449 1.168 1.28 1.168 2.229c0 .75-.145 1.874-1.338 2.15l-4.543.435c-1.308 0-2.369-1.157-2.369-2.585c0-.95.47-1.78 1.169-2.23c-.697-.425-1.169-1.238-1.169-2.172c0-.922.46-1.727 1.143-2.157c-.685-.457-1.143-1.282-1.143-2.224");
}

.ujydyib8d {
  d: path("M17.962 10.42c3.188 1.826 5.35 5.346 5.35 9.273c0 1.603-.361 3.112-1.004 4.453h4.13c1.587 0 2.873 1.298 2.873 2.899s-1.286 2.898-2.872 2.898H14.084q-.33 0-.634-.008q-.21.008-.419.008c-6.874 0-10.342-4.551-10.342-10.281c0-4.284 2.608-8.067 6.298-9.703l.035-.02c1.424-.605 4.223-2.804 6.61-6.504c1.192-1.547 2.997-1.764 4.257-.791c1.26.972 1.371 2.784.581 4.073c-.54.883-1.911 2.85-2.508 3.703");
}

.uo58ai19j {
  stop-color: var(--svg-color--402332, #402332);
}

.ushh2_8bd {
  stop-color: var(--svg-color--49302e, #49302E);
  stop-opacity: 0;
}

.uyg-dupgi {
  stop-color: var(--svg-color--190c0c, #190C0C);
}

.uzwc_ugjd {
  stop-color: var(--svg-color--3d222e, #3D222E);
}

.wn-9kxdtp {
  stop-color: var(--svg-color--3f2a29, #3F2A29);
}

.xm34y9b_d {
  stop-color: var(--svg-color--65514f, #65514F);
}

.y0afrubvw {
  stop-color: var(--svg-color--49302e, #49302E);
}

.z_9l1gcue {
  stop-color: var(--svg-color--4f3633, #4F3633);
}

.zfrtjb4gd {
  stop-color: var(--svg-color--594744, #594744);
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
