<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="te5k6e35r"/><path class="efxz7qqkp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lawn-mower-electric" /></template>
<style>
.efxz7qqkp {
  d: path("M7.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-8.75-13C2.5 8 2 14 4 21.5");
}

.te5k6e35r {
  d: path("M6.5 17.5v-3A2.5 2.5 0 0 1 9 12h6a5.5 5.5 0 0 1 5.5 5.5Zm3-5.5l-3-9H5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
