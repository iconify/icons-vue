<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vo016xc9w"/><path class="nsgzosmuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:black-hole-jet" /></template>
<style>
.nsgzosmuy {
  d: path("M15.234 2.898L14 8.536m4.266-3.888L14 8.536M5.734 19.352L10 15.464m-1.234 5.638L10 15.464");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vo016xc9w {
  fill: currentColor;
  d: path("M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
