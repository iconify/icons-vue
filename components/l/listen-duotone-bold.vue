<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ho-xl5v5i"/><path class="mm7_1psrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:listen-duotone-bold" /></template>
<style>
.ho-xl5v5i {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 21v-4c-2 -1 -3 -4 -3 -7a6 6 0 0 1 12 0c0 2 -2 3 -3 3s-2 -1 -2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mm7_1psrl {
  d: path("M8 21v-4c-2 -1 -3 -4 -3 -7a6 6 0 0 1 12 0c0 2 -2 3 -3 3s-2 -1 -2 -2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
