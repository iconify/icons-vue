<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cd_bak0id"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-clock-corner-round" /></template>
<style>
.cd_bak0id {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3H9a4 4 0 0 0-4 4v10a4 4 0 0 0 4 4m4-18l6 6m-6-6v4a2 2 0 0 0 2 2h4m-7 8a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
