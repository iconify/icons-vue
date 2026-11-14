<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivw2gca1t"/><path class="wqvvlw7mc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:format-painter" /></template>
<style>
.ivw2gca1t {
  d: path("M3.5 3h13v6h-13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqvvlw7mc {
  d: path("M16.5 6H19a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1h-6a1 1 0 0 0-1 1v1.5m-1.5 0h3V21h-3Z");
}

</style>
