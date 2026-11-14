<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="drrm4-boz"/><path class="pos7keb4z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ballot-box" /></template>
<style>
.drrm4-boz {
  d: path("M3.5 11.5h17v10h-17Zm4.5 0v-8a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v8");
}

.pos7keb4z {
  d: path("m10.25 7l1.25 1.25L13.75 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
