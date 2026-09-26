<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmpapfwyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:gallery-vertical" /></template>
<style>
.qmpapfwyd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5 7L19 7C20.10457 7 21 7.89543 21 9L21 15C21 16.10457 20.10457 17 19 17L5 17C3.89543 17 3 16.10457 3 15L3 9C3 7.89543 3.89543 7 5 7ZM3 3H21M3 21H21");
}

</style>
