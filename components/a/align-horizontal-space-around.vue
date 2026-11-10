<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o3mwu1bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-around" /></template>
<style>
.o3mwu1bfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 2V22M4 2V22M9 9V15C9 16.11 9.9033 17 11 17H12H13C14.1125 17 15 16.105 15 15V9C15 7.896 14.1045 7 13 7H12H11C9.8954 7 9 7.901 9 9Z");
}

</style>
