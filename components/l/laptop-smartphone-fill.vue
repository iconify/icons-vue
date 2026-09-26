<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ijh4fpfgt"/><path class="n5gl7ccqk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-fill" /></template>
<style>
.ijh4fpfgt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 19V13C23 10.7909 21.2091 9 19 9H16C13.7909 9 12 10.7909 12 13V19C12 21.2091 13.7909 23 16 23H19C21.2091 23 23 21.2091 23 19ZM17 13L18 13C18.5523 13 19 13.4477 19 14C19 14.5523 18.5523 15 18 15L17 15C16.4477 15 16 14.5523 16 14C16 13.4477 16.4477 13 17 13Z");
  stroke: none;
}

.n5gl7ccqk {
  d: path("M4 14V4C4 2.8954 4.8954 2 6 2H18C19.1046 2 20 2.8954 20 4M9 18H4C2.8954 18 2 17.1046 2 16V14.5C2 14.2239 2.2239 14 2.5 14H9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
