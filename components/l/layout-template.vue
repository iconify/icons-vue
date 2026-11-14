<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv4eh4buw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-template" /></template>
<style>
.sv4eh4buw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.125 2.5h.75A2.625 2.625 0 0 1 8.5 5.125v13.75A2.625 2.625 0 0 1 5.875 21.5h-.75A2.625 2.625 0 0 1 2.5 18.875V5.125A2.625 2.625 0 0 1 5.125 2.5m8.75 0h5A2.625 2.625 0 0 1 21.5 5.125v.75A2.625 2.625 0 0 1 18.875 8.5h-5a2.625 2.625 0 0 1-2.625-2.625v-.75A2.625 2.625 0 0 1 13.875 2.5m0 8.75h5a2.625 2.625 0 0 1 2.625 2.625v5a2.625 2.625 0 0 1-2.625 2.625h-5a2.625 2.625 0 0 1-2.625-2.625v-5a2.625 2.625 0 0 1 2.625-2.625");
}

</style>
