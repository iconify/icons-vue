<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bqyc33b5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-horizontal" /></template>
<style>
.bqyc33b5s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 3L15 3C16.10457 3 17 3.89543 17 5L17 19C17 20.10457 16.10457 21 15 21L9 21C7.89543 21 7 20.10457 7 19L7 5C7 3.89543 7.89543 3 9 3ZM3 3V21M21 3V21");
}

</style>
