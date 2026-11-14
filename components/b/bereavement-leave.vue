<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzonuor8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bereavement-leave" /></template>
<style>
.kzonuor8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.75 4.25L13.5 7l2.75-.75l.75 2.5l2.75-.5L17.5 12a4 4 0 0 1-7-4ZM12 13.5v8m0-1c-3.25 0-6.25-2.5-7-6.25c3.5.25 6.25 2.5 7 6.25");
}

</style>
