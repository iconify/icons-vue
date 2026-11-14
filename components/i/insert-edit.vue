<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hw-j7lbvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:insert-edit" /></template>
<style>
.hw-j7lbvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 19h19M4.75 13.5h2a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 6.75 19h-2A1.75 1.75 0 0 1 3 17.25v-2a1.75 1.75 0 0 1 1.75-1.75m12.5 0h2A1.75 1.75 0 0 1 21 15.25v2A1.75 1.75 0 0 1 19.25 19h-2a1.75 1.75 0 0 1-1.75-1.75v-2a1.75 1.75 0 0 1 1.75-1.75M11 5h2a1.75 1.75 0 0 1 1.75 1.75v2A1.75 1.75 0 0 1 13 10.5h-2a1.75 1.75 0 0 1-1.75-1.75v-2A1.75 1.75 0 0 1 11 5");
}

</style>
