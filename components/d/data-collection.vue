<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fqvmgvdru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-collection" /></template>
<style>
.fqvmgvdru {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.923 9h8.154a1.729 1.729 0 0 1 1.173 3l-2.687 2.48A1.75 1.75 0 0 0 14 15.766v3.484A1.75 1.75 0 0 1 12.25 21h-.5A1.75 1.75 0 0 1 10 19.25v-3.484a1.75 1.75 0 0 0-.563-1.286L6.75 12a1.729 1.729 0 0 1 1.173-3M7.5 3.5h.01m4.49.75h.01m4.49-.75h.01");
}

</style>
