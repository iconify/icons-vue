<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spv1oibny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:burn-injury" /></template>
<style>
.spv1oibny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 6.5l9 .75c1 0 1.75-.5 2.5-1.25l1.5-1.5c.75-.75 2-.25 1.75.75L16.75 7H19c1.4 0 2.5 1.1 2.5 2.5V11c0 .774-.336 1.456-.874 1.912m-5.303.343L11.5 13l-9 1m19-3.75H19m-1 4c2 1.75 3 3 3 4.5c0 1.75-1.25 3-3 3s-3-1.25-3-3c0-1 .5-1.75 1.25-2.25c0 1 .5 1.5 1.25 1.5c0-1.25-.25-2.5.5-3.75");
}

</style>
