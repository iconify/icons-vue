<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#imjQQJN)" class="c0bglzbgx"/><rect fill="url(#iycmMOe)" class="c0bglzbgx"/><rect fill="url(#inuLDxe)" class="c0bglzbgx"/><rect fill="url(#isQm6bc)" class="kla-nsx9y"/><g filter="url(#ioURQQc)"><path fill="url(#iyDGh3c)" clip-rule="evenodd" class="i88ky9vqt"/></g><ellipse class="kld8wwqux"/><ellipse fill="url(#iqMPbJd)" class="sousm-bga"/><ellipse fill="url(#iXC7b0s)" class="sousm-bga"/><g filter="url(#iG5d3Fm)"><path class="scqlbbb3b"/></g><g filter="url(#iH1zvyv)"><path class="v_16dsi5h"/></g><path fill="url(#ij2dOid)" class="n91vrkbzi"/><path fill="url(#ic9Rcke)" class="n91vrkbzi"/><g filter="url(#iykQkjd)"><path fill="url(#i3x1Ffc)" class="ruxxvob0s"/></g><defs><linearGradient id="imjQQJN" x1="28.109" x2="3.047" y1="28.688" y2="28.688" gradientUnits="userSpaceOnUse"><stop class="wqe4hgbvc"/><stop offset="1" class="omvflacjo"/></linearGradient><linearGradient id="iycmMOe" x1="29.922" x2="27.266" y1="27.813" y2="27.813" gradientUnits="userSpaceOnUse"><stop class="clous5b9l"/><stop offset="1" class="em-tdzbbm"/></linearGradient><linearGradient id="inuLDxe" x1="2.078" x2="4.828" y1="27.688" y2="27.688" gradientUnits="userSpaceOnUse"><stop offset=".557" class="minmm7bjg"/><stop offset="1" class="v44i3221y"/></linearGradient><linearGradient id="iyDGh3c" x1="25.625" x2="7.875" y1="9.75" y2="24.438" gradientUnits="userSpaceOnUse"><stop class="uqq__nbae"/><stop offset="1" class="qachdyiuz"/></linearGradient><linearGradient id="iqMPbJd" x1="19.313" x2="21.094" y1="17.688" y2="17.688" gradientUnits="userSpaceOnUse"><stop offset=".228" class="gzto6fbfn"/><stop offset="1" class="de5n20bkf"/></linearGradient><linearGradient id="ij2dOid" x1="17.25" x2="17.25" y1="9.688" y2="27" gradientUnits="userSpaceOnUse"><stop class="aa1s23ikb"/><stop offset="1" class="qgx211bpe"/></linearGradient><linearGradient id="ic9Rcke" x1="18.313" x2="18.313" y1="29.906" y2="26.063" gradientUnits="userSpaceOnUse"><stop offset=".894" class="lok4kt4na"/><stop offset="1" class="r4fju6bru"/></linearGradient><linearGradient id="i3x1Ffc" x1="9.645" x2="9.645" y1="12.93" y2="21.996" gradientUnits="userSpaceOnUse"><stop class="ajz_v4uxp"/><stop offset="1" class="mfrnh_cso"/></linearGradient><filter id="ioURQQc" width="25.525" height="15.731" x="3.237" y="9.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.509804 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_21410"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.509804 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_21410" result="effect2_innerShadow_18_21410"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.709804 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21410" result="effect3_innerShadow_18_21410"/></filter><filter id="iG5d3Fm" width="5.112" height="18.8" x="14.412" y="7.912" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21410" stdDeviation=".2"/></filter><filter id="iH1zvyv" width="4.813" height="3.906" x="14.563" y="26.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_21410" stdDeviation=".125"/></filter><filter id="iykQkjd" width="4.719" height="9.416" x="7.21" y="12.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.0901961 0 0 0 0 0.521569 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_18_21410"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_18_21410" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_18_21410"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.996078 0 0 0 0 0.992157 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_21410" result="effect3_innerShadow_18_21410"/></filter><radialGradient id="isQm6bc" cx="0" cy="0" r="1" gradientTransform="matrix(12.93753 14.5 -19.01468 16.96571 2.688 8.75)" gradientUnits="userSpaceOnUse"><stop class="kmcyfsbcm"/><stop offset="1" class="dzvz5jvhv"/></radialGradient><radialGradient id="iXC7b0s" cx="0" cy="0" r="1" gradientTransform="rotate(-40.802 34.41 -19.1)scale(4.83012 4.74756)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yp0r0acfw"/><stop offset=".987" class="lk8zkoa4i"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:dollar-banknote" /></template>
<style>
.aa1s23ikb {
  stop-color: var(--svg-color--ffd425, #FFD425);
}

.ajz_v4uxp {
  stop-color: var(--svg-color--efeaea, #EFEAEA);
}

.c0bglzbgx {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 11.625px;
  rx: 2.2px;
}

.clous5b9l {
  stop-color: var(--svg-color--1c8f60, #1C8F60);
}

.de5n20bkf {
  stop-color: var(--svg-color--269553, #269553);
  stop-opacity: 0;
}

.dzvz5jvhv {
  stop-color: var(--svg-color--20cf5e, #20CF5E);
}

.em-tdzbbm {
  stop-color: var(--svg-color--1c8f60, #1C8F60);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gzto6fbfn {
  stop-color: var(--svg-color--269553, #269553);
}

.i88ky9vqt {
  fill-rule: evenodd;
  d: path("M27.063 10.156H4.938a.75.75 0 0 0-.75.75v12.532c0 .414.335.75.75.75h22.125a.75.75 0 0 0 .75-.75V10.906a.75.75 0 0 0-.75-.75m-22.125-.75a1.5 1.5 0 0 0-1.5 1.5v12.532a1.5 1.5 0 0 0 1.5 1.5h22.125a1.5 1.5 0 0 0 1.5-1.5V10.906a1.5 1.5 0 0 0-1.5-1.5z");
}

.kla-nsx9y {
  width: 27.844px;
  height: 18.281px;
  x: 2.078px;
  y: 8.031px;
  rx: 2.2px;
}

.kld8wwqux {
  cx: 20.844px;
  cy: 17.172px;
  fill: var(--svg-color--289d5b, #289D5B);
  rx: 4.625px;
  ry: 4.266px;
}

.kmcyfsbcm {
  stop-color: var(--svg-color--31de74, #31DE74);
}

.lk8zkoa4i {
  stop-color: var(--svg-color--16793d, #16793D);
}

.lok4kt4na {
  stop-color: var(--svg-color--cc8139, #CC8139);
}

.mfrnh_cso {
  stop-color: var(--svg-color--eae3e3, #EAE3E3);
}

.minmm7bjg {
  stop-color: var(--svg-color--195840, #195840);
}

.n91vrkbzi {
  d: path("M15.063 8.031h4.375v21.875h-4.375z");
}

.omvflacjo {
  stop-color: var(--svg-color--116245, #116245);
}

.qachdyiuz {
  stop-color: var(--svg-color--27a05a, #27A05A);
}

.qgx211bpe {
  stop-color: var(--svg-color--ffad24, #FFAD24);
}

.r4fju6bru {
  stop-color: var(--svg-color--cc8139, #CC8139);
  stop-opacity: 0;
}

.ruxxvob0s {
  d: path("M9.04 13.543a.613.613 0 0 1 1.226 0v.675c1.001.245 1.482 1.034 1.55 1.696c.04.377-.167.633-.497.667a.6.6 0 0 1-.658-.535c-.022-.216-.138-.843-1.06-.843c-1.32 0-1.351 1.742.18 1.742c.656 0 1.35.38 1.664.817c.327.454.434.953.363 1.454c-.192.842-.778 1.341-1.542 1.517v.65a.613.613 0 1 1-1.227 0v-.636c-.856-.183-1.465-.797-1.574-1.731c-.039-.33.167-.628.496-.667a.6.6 0 0 1 .666.526c.02.164.085.395.228.572c.121.152.328.287.747.287c.52 0 .797-.19.93-.406c.406-.586-.07-1.312-.778-1.312c-.949-.04-1.414-.28-1.793-.692a1.9 1.9 0 0 1-.496-1.258c0-.297.087-.778.413-1.175a2.02 2.02 0 0 1 1.161-.692z");
}

.scqlbbb3b {
  fill: var(--svg-color--127531, #127531);
  d: path("M14.969 8.313h4.156v18h-4.312z");
}

.sousm-bga {
  cx: 20.844px;
  cy: 17.172px;
  rx: 4.625px;
  ry: 4.266px;
}

.uqq__nbae {
  stop-color: var(--svg-color--24a35b, #24A35B);
}

.v_16dsi5h {
  fill: var(--svg-color--0b3f2e, #0B3F2E);
  d: path("M14.984 29.719h4.141v-3.407h-4.312z");
}

.v44i3221y {
  stop-color: var(--svg-color--195840, #195840);
  stop-opacity: 0;
}

.wqe4hgbvc {
  stop-color: var(--svg-color--12724a, #12724A);
}

.yp0r0acfw {
  stop-color: var(--svg-color--249755, #249755);
  stop-opacity: 0;
}

</style>
