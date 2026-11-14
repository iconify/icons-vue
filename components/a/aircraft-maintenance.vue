<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p6ri426ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-maintenance" /></template>
<style>
.p6ri426ad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.203 19.101L12 18.5l-2.75.75v-1.5l1.25-1.25V11l-8 1.75V11l8-3.5V5c0-1.5.4-2.5 1.5-2.5s1.5 1 1.5 2.5v2.5l8 3.5v1.75l-8-1.75v5.5l1.25 1.25v.767M20 15.5a1.75 1.75 0 1 0 1.75 1.75m-3 1.25l-2.25 2.25");
}

</style>
