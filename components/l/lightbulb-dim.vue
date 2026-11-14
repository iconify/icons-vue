<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="frpdz9bxu"/><path class="ub1orqa5w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:lightbulb-dim" /></template>
<style>
.frpdz9bxu {
  d: path("M9.5 15a6.5 6.5 0 1 1 5 0v2.5h-5Zm.75 5.5h3.5");
}

.ub1orqa5w {
  fill: currentColor;
  d: path("M12 5.25a3.75 3.75 0 0 0 0 7.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
