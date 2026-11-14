<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i8h9m8bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fish-stringer" /></template>
<style>
.i8h9m8bqi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 9L12 3.5L19.5 9M12 3.5V9M4.5 9c3 1 3 5.5.75 8l1.5 3.5h-4.5l1.5-3.5C1.5 14.5 1.5 10 4.5 9M12 9c3 1 3 5.5.75 8l1.5 3.5h-4.5l1.5-3.5C9 14.5 9 10 12 9m7.5 0c3 1 3 5.5.75 8l1.5 3.5h-4.5l1.5-3.5c-2.25-2.5-2.25-7 .75-8");
}

</style>
