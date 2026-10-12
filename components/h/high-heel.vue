<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="linpexbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:high-heel" /></template>
<style>
.linpexbya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.25v-.5a2 2 0 0 1 2-2C8 15.75 10.5 14 12.5 11l2.25-3.5a1.75 1.75 0 0 1 3 .05l3.5 5.7v2.25c-4.25 0-7.75 1.5-9.75 3.75H3.75a1 1 0 0 1-1-1m17.25-2v5");
}

</style>
