<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snqeu6faj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lungs" /></template>
<style>
.snqeu6faj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 8.25V18.5a2.5 2.5 0 0 1-2.5 2.5h-1.5a2.5 2.5 0 0 1-2.5-2.5v-1.75c0-4.5 2.15-9 4.5-10.4c1-.6 2 .25 2 1.4Zm5.5 0V18.5a2.5 2.5 0 0 0 2.5 2.5h1.5a2.5 2.5 0 0 0 2.5-2.5v-1.75c0-4.5-2.15-9-4.5-10.4c-1-.6-2 .25-2 1.4ZM12 2.75v7.5c0 1.5-.9 2.5-2.75 3m2.75-3c0 1.5.9 2.5 2.75 3");
}

</style>
