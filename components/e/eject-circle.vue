<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="az8y93_uz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eject-circle" /></template>
<style>
.az8y93_uz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.78 5.22l5.69 7.06q.78.97-.47.97H6q-1.25 0-.47-.97l5.69-7.06q.78-.97 1.56 0M4.75 18.75h14.5");
}

</style>
