<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mc8-8wghm"/><path class="gsf8otg5p"/><path class="sz5tfw-dc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:internship-posting" /></template>
<style>
.gsf8otg5p {
  d: path("M7 14.25v4.25c0 1.25 2.25 2.5 5 2.5s5-1.25 5-2.5v-4.25M9.75 4.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

.mc8-8wghm {
  d: path("m12 9l8.5 3.75L12 16.5l-8.5-3.75Z");
}

.sz5tfw-dc {
  d: path("M12 6.75v6h8.5v4.75");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
