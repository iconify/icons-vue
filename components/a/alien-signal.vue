<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="truhmbcud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:alien-signal" /></template>
<style>
.truhmbcud {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 11c2.5 0 4.5 1.75 4.5 4c0 2.75-2.5 6.25-4.5 6.25s-4.5-3.5-4.5-6.25c0-2.25 2-4 4.5-4m-2.5 4.25l1.5.75m3.5-.75l-1.5.75m1.71-6.92a5.5 5.5 0 0 1 4.46 4.46m-3.81-8.15a9.25 9.25 0 0 1 7.5 7.5");
}

</style>
