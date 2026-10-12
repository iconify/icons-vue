<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y44_8uetv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diving-fins" /></template>
<style>
.y44_8uetv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 2.75H10q.75 0 .73.75l-.46 17q-.02.75-.76.65l-6.02-.8q-.74-.1-.56-.83L6.82 3.48q.18-.73.93-.73m8.5 0H14q-.75 0-.73.75l.46 17q.02.75.76.65l6.02-.8q.74-.1.56-.83L17.18 3.48q-.18-.73-.93-.73M8 9l-1.25 9.5M16 9l1.25 9.5");
}

</style>
