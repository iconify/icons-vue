<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsvqgkbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crossroads-sign" /></template>
<style>
.nsvqgkbdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.856 3.856l3.788 3.788a2.625 2.625 0 0 1 0 3.712l-3.788 3.788a2.625 2.625 0 0 1-3.712 0l-3.788-3.788a2.625 2.625 0 0 1 0-3.712l3.788-3.788a2.625 2.625 0 0 1 3.712 0M12 17v5m0-16v7M8.5 9.5h7");
}

</style>
