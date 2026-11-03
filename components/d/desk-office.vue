<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtq5myb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:desk-office" /></template>
<style>
.xtq5myb4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 22L3 13C3 12.4477 3.4477 12 4 12L20 12C20.5523 12 21 12.4477 21 13L21 21C21 21.5523 20.5523 22 20 22L15 22C14.4477 22 14 21.5523 14 21L14 12M21 17L14 17M12 12L12 8M12 8L8.5 8C7.6716 8 7 7.3284 7 6.5L7 3.5C7 2.6716 7.6716 2 8.5 2L15.5 2C16.3284 2 17 2.6716 17 3.5L17 6.5C17 7.3284 16.3284 8 15.5 8Z");
}

</style>
