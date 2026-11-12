<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xpzbxokqs"/><path class="jge_j1bmb"/><path class="cugumcbbj"/><path class="qmsms8bjm"/><path class="z5zog32ca"/><path class="i-2prw66f"/><path class="mzdmjcc3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:house-linear" /></template>
<style>
.cugumcbbj {
  d: path("M15.5 5.5V3.5C15.5 3.22386 15.7239 3 16 3H18.5C18.7761 3 19 3.22386 19 3.5V8.5");
}

.i-2prw66f {
  d: path("M15 22V17C15 15.5858 15 14.8787 14.5607 14.4393C14.1213 14 13.4142 14 12 14C10.5858 14 9.87868 14 9.43934 14.4393C9 14.8787 9 15.5858 9 17V22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jge_j1bmb {
  d: path("M2 11L10.1259 4.49928C11.2216 3.62276 12.7784 3.62276 13.8741 4.49928L22 11");
}

.mzdmjcc3w {
  d: path("M14 9.5C14 10.6046 13.1046 11.5 12 11.5C10.8954 11.5 10 10.6046 10 9.5C10 8.39543 10.8954 7.5 12 7.5C13.1046 7.5 14 8.39543 14 9.5Z");
}

.qmsms8bjm {
  d: path("M4 22V9.5");
}

.xpzbxokqs {
  d: path("M22 22L2 22");
}

.z5zog32ca {
  d: path("M20 22V9.5");
}

</style>
