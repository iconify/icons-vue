<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uewh1bbor"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:assets-liabilities" /></template>
<style>
.uewh1bbor {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4v16.5m-3.5 0h7M5.5 7h13m-13 0l-3 7h6zm-3 7a3 3 0 0 0 6 0m10-7l-3 7h6zm-3 7a3 3 0 0 0 6 0");
}

</style>
