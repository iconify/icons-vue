<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zyzj8zban"/><path class="lupg-8tzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:farm" /></template>
<style>
.lupg-8tzu {
  d: path("M9.5 8V4.25h2V10m3.25.5a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0ZM18 13.75v6.75m-12.25 0v-4h3v4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zyzj8zban {
  d: path("m2.5 10.5l4.75-4.75L12 10.5v10H2.5Z");
}

</style>
