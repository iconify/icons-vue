<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ow92_3bej"/><path class="e8b163tgy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:crochet-hook" /></template>
<style>
.e8b163tgy {
  d: path("m12.15 12.91l-1.06-1.06q-.53-.53-1.06 0l-3.18 3.18q-.53.53 0 1.06l1.06 1.06q.53.53 1.06 0l3.18-3.18q.53-.53 0-1.06");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ow92_3bej {
  d: path("m3.75 20.25l3.63-3.63m4.24-4.24l6.63-6.63a1.77 1.77 0 0 0-2.5-2.5l-.5.5");
}

</style>
