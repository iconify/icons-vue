<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jgdvtfbec"/><path class="ao8_yebye"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electric-locomotive" /></template>
<style>
.ao8_yebye {
  d: path("M5 20a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm8 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.jgdvtfbec {
  d: path("M2.5 3h19M9 9.5l4-3.25L10.5 3m-8 15v-6.5a2 2 0 0 1 2-2H17l4.5 4.5v4Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
