<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5kszfb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bookworm-insect" /></template>
<style>
.f5kszfb-v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18.176 16.434q1.587-.092 3.324.066V4Q16 3.5 12 5.5Q8 3.5 2.5 4v12.5Q8 16 12 18q.425-.213.867-.397M12 5.5V18m2.5 2q1.75-2.5 3.5 0t3.5 0m0 0h.01");
}

</style>
