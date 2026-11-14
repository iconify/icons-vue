<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7oq6kbjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:first-aid-training" /></template>
<style>
.t7oq6kbjm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6Q9 3.75 3 4.5v14q6-.75 9 1.5q3-2.25 9-1.5v-14q-6-.75-9 1.5Zm0 0v14m4.5-10.5V13m-1.75-1.75h3.5");
}

</style>
