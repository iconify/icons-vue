<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s4nfw7bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:finds-bag" /></template>
<style>
.s4nfw7bpk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 9C3 11 3 21.5 8 21.5h5c5 0 5-10.5-1.5-12.5Zm0 0L7 4.5h7L11.5 9m0 0l5.25-2m0-.5a2.25 3 0 1 0 4.5 0a2.25 3 0 1 0-4.5 0");
}

</style>
