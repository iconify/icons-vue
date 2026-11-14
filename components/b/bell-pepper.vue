<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lv3e9mb5j"/><path class="lj138rs2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bell-pepper" /></template>
<style>
.lj138rs2p {
  d: path("M12 6.5v-2q0-2 2.5-2");
}

.lv3e9mb5j {
  d: path("M12 6.5c-4.5-2-8.5 0-8.5 5.5c0 5 1.5 9.5 4.25 9.5q2 0 2.25-1.5q2 2.5 4 0q.25 1.5 2.25 1.5C19 21.5 20.5 17 20.5 12c0-5.5-4-7.5-8.5-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
