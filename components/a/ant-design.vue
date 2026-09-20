<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGLtho8dDK" x1="62.102%" x2="108.197%" y1="0%" y2="37.864%"><stop offset="0%" class="nshrtr0ga"/><stop offset="100%" class="a41uemsow"/></linearGradient><linearGradient id="SVGN6GESbiL" x1="69.644%" x2="54.043%" y1="0%" y2="108.457%"><stop offset="0%" class="k57-dfofk"/><stop offset="37.86%" class="h-gmbhbyv"/><stop offset="100%" class="bsvif8byf"/></linearGradient><linearGradient id="SVGAM3vtM4q" x1="69.691%" x2="16.723%" y1="-12.974%" y2="117.391%"><stop offset="0%" class="e-yhjf7eo"/><stop offset="41.473%" class="gaabew7_c"/><stop offset="100%" class="x2t-8obkz"/></linearGradient><linearGradient id="SVGcuaZ2bVd" x1="68.128%" x2="30.44%" y1="-35.691%" y2="114.943%"><stop offset="0%" class="c1-e3jbwl"/><stop offset="51.264%" class="gaabew7_c"/><stop offset="100%" class="x2t-8obkz"/></linearGradient></defs><g class="ft5dv1b6b"><path fill="url(#SVGLtho8dDK)" class="iqlt-wbaw"/><path fill="url(#SVGN6GESbiL)" class="nezeror1e"/><path fill="url(#SVGAM3vtM4q)" class="d1u6u468s"/><ellipse fill="url(#SVGcuaZ2bVd)" class="ykww2cb3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:ant-design" /></template>
<style>
.a41uemsow {
  stop-color: var(--svg-color--2ec7ff, #2ec7ff);
}

.bsvif8byf {
  stop-color: var(--svg-color--0a60ff, #0a60ff);
}

.c1-e3jbwl {
  stop-color: var(--svg-color--fa8e7d, #fa8e7d);
}

.d1u6u468s {
  d: path("M196.647 173.754c5.408 5.404 14.176 5.404 19.584 0l34.739-34.71a15.396 15.396 0 0 0 0-21.812l-35.041-34.89c-5.421-5.397-14.192-5.389-19.603.018c-5.408 5.404-5.408 14.164 0 19.568l23.667 23.648c1.503 1.502 1.503 3.781 0 5.283l-23.346 23.327c-5.408 5.404-5.408 14.165 0 19.568");
}

.e-yhjf7eo {
  stop-color: var(--svg-color--fa816e, #fa816e);
}

.ft5dv1b6b {
  fill: none;
}

.gaabew7_c {
  stop-color: var(--svg-color--f74a5c, #f74a5c);
}

.h-gmbhbyv {
  stop-color: var(--svg-color--148eff, #148eff);
}

.iqlt-wbaw {
  d: path("M116.85 4.545L4.53 116.775a15.396 15.396 0 0 0 0 21.812l112.32 112.229c6.039 6.033 15.792 6.033 21.83 0l47.095-47.056c5.408-5.404 5.408-14.165 0-19.568s-14.176-5.404-19.584 0l-35.702 35.672c-1.503 1.502-3.784 1.502-5.287 0l-89.696-89.622c-1.503-1.502-1.503-3.781 0-5.283l89.696-89.623c1.503-1.501 3.784-1.501 5.287 0l35.702 35.673c5.408 5.404 14.176 5.404 19.584 0s5.408-14.164 0-19.568l-47.09-47.05c-6.063-5.904-15.82-5.856-21.835.154");
}

.k57-dfofk {
  stop-color: var(--svg-color--29cdff, #29cdff);
}

.nezeror1e {
  d: path("M116.85 4.545L4.53 116.775a15.396 15.396 0 0 0 0 21.812l112.32 112.229c6.039 6.033 15.792 6.033 21.83 0l47.095-47.056c5.408-5.404 5.408-14.165 0-19.568s-14.176-5.404-19.584 0l-35.702 35.672c-1.503 1.502-3.784 1.502-5.287 0l-89.696-89.622c-1.503-1.502-1.503-3.781 0-5.283l89.696-89.623c3.742-3.226 9.849-9.76 18.815-11.29q9.996-1.703 21.857 7.5L138.686 4.39c-6.064-5.903-15.82-5.855-21.836.155");
}

.nshrtr0ga {
  stop-color: var(--svg-color--4285eb, #4285eb);
}

.x2t-8obkz {
  stop-color: var(--svg-color--f51d2c, #f51d2c);
}

.ykww2cb3j {
  cx: 128.327px;
  cy: 128.242px;
  rx: 30.327px;
  ry: 30.302px;
}

</style>
