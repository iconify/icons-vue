<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":201};
const content = `<defs><linearGradient id="SVGn7MQdcpE" x1="128.8" x2="227.2" y1="104.44" y2="104.44" gradientUnits="userSpaceOnUse"><stop class="jderzofof"/><stop offset="1" class="zl05wtblf"/></linearGradient><linearGradient id="SVGg7gAEeAi" x1="136.22" x2="78.5" y1="91.32" y2="91.19" gradientUnits="userSpaceOnUse"><stop offset=".15" class="oh10ogb5s"/><stop offset="1" class="k5i43vf8q"/></linearGradient><radialGradient id="SVGYttsNcac" cx="0" cy="0" r="1" gradientTransform="matrix(-159.725 0 0 -135.852 160.325 96)" gradientUnits="userSpaceOnUse"><stop offset=".15" class="ovzu8acsw"/><stop offset="1" class="s5swet9dp"/></radialGradient><filter id="SVG5vOj3Sef" width="166" height="180" x="45.91" y="8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_37584_9338" stdDeviation="14"/></filter></defs><g transform="translate(-11.636 -39.273)scale(1.45454)"><path fill="url(#SVGn7MQdcpE)" class="q0h4dxh-v"/><path fill="url(#SVGYttsNcac)" class="tl8z08gok"/><g filter="url(#SVG5vOj3Sef)" mask="url(#SVGUq8hDd0H)"><path fill="url(#SVGg7gAEeAi)" class="a8bfwtbfr"/></g><circle class="fek7y8p6o"/></g><mask id="SVGUq8hDd0H" width="129" height="138" x="8" y="27" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path class="qgyng4jqy"/></mask>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:google-meet" /></template>
<style>
.a8bfwtbfr {
  d: path("m73.906 99.198l110-63.198v124z");
}

.fek7y8p6o {
  cx: 38px;
  cy: 135px;
  r: 14px;
  fill: var(--svg-color--fff, #fff);
}

.jderzofof {
  stop-color: var(--svg-color--f6a100, #f6a100);
}

.k5i43vf8q {
  stop-color: var(--svg-color--ffdbf5, #ffdbf5);
  stop-opacity: 0;
}

.oh10ogb5s {
  stop-color: var(--svg-color--ffb5e8, #ffb5e8);
}

.ovzu8acsw {
  stop-color: var(--svg-color--ffe921, #ffe921);
}

.q0h4dxh-v {
  d: path("M110.015 108.88c-6.829-4.718-6.921-14.778-.179-19.62L165 49.643c7.94-5.701 19-.038 19 9.737v77.755c0 9.675-10.861 15.359-18.821 9.859z");
}

.qgyng4jqy {
  fill: var(--svg-color--fff, #fff);
  d: path("M8 71c0-24.3 19.7-44 44-44h64c11.046 0 20 8.954 20 20v98c0 11.046-8.954 20-20 20H28c-11.046 0-20-8.954-20-20z");
}

.s5swet9dp {
  stop-color: var(--svg-color--fec700, #fec700);
}

.tl8z08gok {
  d: path("M8 71c0-24.3 19.7-44 44-44h64c11.046 0 20 8.954 20 20v98c0 11.046-8.954 20-20 20H28c-11.046 0-20-8.954-20-20z");
}

.zl05wtblf {
  stop-color: var(--svg-color--ffbe00, #ffbe00);
}

</style>
