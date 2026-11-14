<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rap34tbfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magnetic-rock" /></template>
<style>
.rap34tbfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.707 15.054l.69-4.836a1.75 1.75 0 0 1 .683-1.153l2.529-1.897a1.75 1.75 0 0 1 1.874-.144l1.841.982a1.75 1.75 0 0 1 .926 1.544v4.543a1.75 1.75 0 0 1-.741 1.43L7.723 17.49a1.75 1.75 0 0 1-1.563.23l-2.274-.758a1.75 1.75 0 0 1-1.179-1.908M14 7h3a5 5 0 0 1 0 10h-3v-3.25h3a1.75 1.75 0 0 0 0-3.5h-3Zm-8.25 7l2.75-3.5");
}

</style>
