<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qj9n9ub9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:golf-hole" /></template>
<style>
.qj9n9ub9a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 14H9v5a2 2 0 0 0 2 2h2a2 2 0 0 0 2-2v-5h6.5M12 18V3m2.084.882l1.166.493a1.493 1.493 0 0 1 0 2.75l-1.166.493A1.5 1.5 0 0 1 12 6.237v-.974a1.5 1.5 0 0 1 2.084-1.381");
}

</style>
