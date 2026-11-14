<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="by4p7cbcs"/><path class="imy2780wd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ball-valve" /></template>
<style>
.by4p7cbcs {
  d: path("M7.5 14a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm-5-3h5v6h-5Zm14 0h5v6h-5Z");
}

.imy2780wd {
  d: path("M12 9.5V5h7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
