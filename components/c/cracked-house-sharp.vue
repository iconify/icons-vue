<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="nkpgljbdx"/><path class="ckqz40b-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cracked-house-sharp" /></template>
<style>
.ckqz40b-o {
  d: path("m14 4.68l-3 4.57l3 3l-2.75 4l1.5 2.5");
}

.nkpgljbdx {
  d: path("m12.38 3.32l8.49 7.11l.38.32h-2v10.5H4.75v-10.5h-2l.38-.32l8.49-7.11L12 3z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
