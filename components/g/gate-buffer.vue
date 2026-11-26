<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5j4xbvzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gate-buffer" /></template>
<style>
.i5j4xbvzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.4856 6.1258L17.4856 11.1258C17.8031 11.3022 18 11.6368 18 12C18 12.3632 17.8031 12.6978 17.4856 12.8742L8.4856 17.8742C8.3371 17.9567 8.1699 18 8 18C7.4477 18 7 17.5523 7 17L7 7C7 6.4477 7.4477 6 8 6C8.1699 6 8.3371 6.0433 8.4856 6.1258ZM2 12L7 12M18 12L22 12");
}

</style>
