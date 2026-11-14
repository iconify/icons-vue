<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn3iyvbqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:co-detected" /></template>
<style>
.mn3iyvbqj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.31 3.254l5.625 3.239a2.63 2.63 0 0 1 1.315 2.275v6.464a2.63 2.63 0 0 1-1.315 2.275l-5.625 3.239a2.63 2.63 0 0 1-2.62 0l-5.625-3.239a2.63 2.63 0 0 1-1.315-2.275V8.768a2.63 2.63 0 0 1 1.315-2.275l5.625-3.239a2.63 2.63 0 0 1 2.62 0M12 7.5V13m0 3.5h.01");
}

</style>
