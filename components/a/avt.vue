<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGLbSNXbOb)" class="pmbjptw7v"/><path fill="url(#SVGVxPP3q4r)" class="s9d2w5bnx"/><path class="dyns2qbut"/><path class="i2uonzbgx"/><defs><linearGradient id="SVGLbSNXbOb" x1="5.683" x2="19.557" y1="20.29" y2="20.29" gradientUnits="userSpaceOnUse"><stop class="sfayo6blr"/><stop offset="1" class="yx0-ohblh"/></linearGradient><linearGradient id="SVGVxPP3q4r" x1="5.688" x2="19.554" y1="21.001" y2="21.001" gradientUnits="userSpaceOnUse"><stop class="sfayo6blr"/><stop offset="1" class="yx0-ohblh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:avt" /></template>
<style>
.dyns2qbut {
  fill: var(--svg-color--5100ff, #5100ff);
  d: path("m20.736 7.642l-6.883 3.22L7.098 21z");
}

.ft5dv1b6b {
  fill: none;
}

.i2uonzbgx {
  fill: var(--svg-color--1d2733, #1d2733);
  d: path("m10.935 3l9.344 15.343l-5.183-2.404l-4.16-8.725z");
}

.pmbjptw7v {
  d: path("m15.224 15.94l5.082 2.414H3.98l11.25-2.414z");
}

.s9d2w5bnx {
  d: path("M10.936 3v4.214l-7.671 9.578z");
}

.sfayo6blr {
  stop-color: var(--svg-color--f2f1f1, #f2f1f1);
}

.yx0-ohblh {
  stop-color: var(--svg-color--1d2733, #1d2733);
}

</style>
