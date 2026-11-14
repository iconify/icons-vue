<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twk6xdbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fiber-intake" /></template>
<style>
.twk6xdbin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M12 8Q8.5 8 8.5 4.5Q12 4.5 12 8m0 4.5q-3.5 0-3.5-3.5Q12 9 12 12.5m0 4.5q-3.5 0-3.5-3.5q3.5 0 3.5 3.5m0-9q3.5 0 3.5-3.5Q12 4.5 12 8m0 4.5q3.5 0 3.5-3.5Q12 9 12 12.5m0 4.5q3.5 0 3.5-3.5q-3.5 0-3.5 3.5");
}

</style>
