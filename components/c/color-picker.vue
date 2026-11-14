<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svpcx-26g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:color-picker" /></template>
<style>
.svpcx-26g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.071 4.929za2 2 0 0 1 0 2.828l-.707.707a2 2 0 0 1-2.828 0a2 2 0 0 1 0-2.828l.707-.707a2 2 0 0 1 2.828 0m-6.364 1.414l4.95 4.95m-2.475-2.475za1.5 1.5 0 0 1 0 2.121l-3.242 3.242a1.5 1.5 0 0 1-.697.395l-1.011.252a.875.875 0 0 1-1.06-1.06l.252-1.011a1.5 1.5 0 0 1 .395-.697l3.242-3.242a1.5 1.5 0 0 1 2.121 0M2.75 19a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0");
}

</style>
