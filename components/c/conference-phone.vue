<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hz3j0jb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:conference-phone" /></template>
<style>
.hz3j0jb8o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 5.25a7 7 0 0 1 10.5 0M9.25 8a4 4 0 0 1 5.5 0m-12 8.5c0-3.5 4.15-6 9.25-6s9.25 2.5 9.25 6v1.25a2 2 0 0 1-2 2H4.75a2 2 0 0 1-2-2Zm4.5-.5h9.5");
}

</style>
