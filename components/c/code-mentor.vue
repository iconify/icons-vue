<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uum3bp8ec"/><path class="p94i_cfxm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-mentor" /></template>
<style>
.p94i_cfxm {
  d: path("m14.75 5l-1.5 1.75l1.5 1.75M17.5 5L19 6.75L17.5 8.5M2.75 10a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM2 21.5c0-4 1.5-6.25 3.25-6.25S8.5 17.5 8.5 21.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uum3bp8ec {
  d: path("M12.5 2.25h7.25a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H14L10.5 14V4.25a2 2 0 0 1 2-2Z");
}

</style>
