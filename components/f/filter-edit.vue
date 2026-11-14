<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi0iiubll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-edit" /></template>
<style>
.bi0iiubll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.101 4h7.298a1.75 1.75 0 0 1 1.376 2.831l-2.901 3.693a1.75 1.75 0 0 0-.374 1.081v4.379a1.75 1.75 0 0 1-.882 1.52L10.75 18A1.17 1.17 0 0 1 9 16.984v-5.379a1.75 1.75 0 0 0-.374-1.081L5.725 6.831A1.75 1.75 0 0 1 7.101 4m8.149 15.875l.155-.699a1.5 1.5 0 0 1 .404-.735l3.316-3.316a1.237 1.237 0 0 1 1.75 0a1.237 1.237 0 0 1 0 1.75l-3.316 3.316a1.5 1.5 0 0 1-.735.404l-.699.155a.733.733 0 0 1-.875-.875");
}

</style>
