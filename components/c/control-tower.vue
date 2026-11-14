<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rtjf72ezz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:control-tower" /></template>
<style>
.rtjf72ezz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.998 3.5h8.004a1.75 1.75 0 0 1 1.644 2.348l-.727 2A1.75 1.75 0 0 1 15.274 9H8.726a1.75 1.75 0 0 1-1.645-1.152l-.727-2A1.75 1.75 0 0 1 7.998 3.5M9.5 9L9 21m5.5-12l.5 12m-9 0h12M12 3.5V9");
}

</style>
