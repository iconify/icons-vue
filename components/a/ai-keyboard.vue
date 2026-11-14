<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gq_uj3xkl"/><path class="wm-zc7p3r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ai-keyboard" /></template>
<style>
.gq_uj3xkl {
  d: path("M14.7 18H2.5V5h19v13h-.2M6.5 9.5h.01m3.99 0h.01m3.99 0h.01m-8.01 4h.01m3.99 0h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wm-zc7p3r {
  d: path("M18 14.75C18 17 19 18 21.25 18C19 18 18 19 18 21.25C18 19 17 18 14.75 18C17 18 18 17 18 14.75Z");
}

</style>
