<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-otfp7jb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:load-balancing" /></template>
<style>
.r-otfp7jb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6v14.5m-4 0h8M4.5 8h15m-17 6h5a2.5 2.5 0 0 1-5 0m.5-.5L4.5 8L6 13.5m10.5.5h5a2.5 2.5 0 0 1-5 0m.5-.5L18.5 8l1.5 5.5M12.025 2.594L10.89 4.012a.3.3 0 0 0 .235.488h.11a.402.402 0 0 1 .39.5a.143.143 0 0 0 .239.136l1.194-1.194a.259.259 0 0 0-.183-.442a.53.53 0 0 1-.522-.616l.022-.134a.198.198 0 0 0-.35-.156");
}

</style>
