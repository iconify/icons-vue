<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj9elu8od"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dusting" /></template>
<style>
.qj9elu8od {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14v7.5M9.5 14l-3-7.5a2.25 2.25 0 0 1 3.75-2a2 2 0 0 1 3.5 0a2.25 2.25 0 0 1 3.75 2l-3 7.5ZM12 7.5V11");
}

</style>
