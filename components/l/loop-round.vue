<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itx63nyal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loop-round" /></template>
<style>
.itx63nyal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 18h2a4 4 0 0 0 4-4v-4a4 4 0 0 0-4-4H7a4 4 0 0 0-4 4v4a4 4 0 0 0 4 4h4m-3 3l3-3l-3-3");
}

</style>
