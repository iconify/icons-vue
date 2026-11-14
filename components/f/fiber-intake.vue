<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npo_a9_9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fiber-intake" /></template>
<style>
.npo_a9_9l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5v19M12 8Q8.5 8 8.5 4.5Q12 4.5 12 8Zm0 4.5q-3.5 0-3.5-3.5Q12 9 12 12.5Zm0 4.5q-3.5 0-3.5-3.5q3.5 0 3.5 3.5Zm0-9q3.5 0 3.5-3.5Q12 4.5 12 8Zm0 4.5q3.5 0 3.5-3.5Q12 9 12 12.5Zm0 4.5q3.5 0 3.5-3.5q-3.5 0-3.5 3.5Z");
}

</style>
