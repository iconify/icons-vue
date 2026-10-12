<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0qixib1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chai-cup" /></template>
<style>
.p0qixib1u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 7.25h9.5a.5.5 0 0 1 .5.55l-.35 2.7H7.1l-.35-2.7a.5.5 0 0 1 .5-.55M7.1 10.5h9.8l-1.05 9.6a1.25 1.25 0 0 1-1.25 1.15H9.4a1.25 1.25 0 0 1-1.25-1.15ZM10 2.75c-.6.75.6 1.5 0 2.25m4-2.25c-.6.75.6 1.5 0 2.25");
}

</style>
