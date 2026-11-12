<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gshkn9qqt"/><path class="b_mqzbbbw"/><path class="r6t4zeiqh"/><path class="lr4e9yb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:code-circle-linear" /></template>
<style>
.b_mqzbbbw {
  d: path("M15.5 9L15.6716 9.17157C17.0049 10.5049 17.6716 11.1716 17.6716 12C17.6716 12.8284 17.0049 13.4951 15.6716 14.8284L15.5 15");
}

.gshkn9qqt {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lr4e9yb5j {
  d: path("M8.4997 9L8.32813 9.17157C6.99479 10.5049 6.32812 11.1716 6.32812 12C6.32812 12.8284 6.99479 13.4951 8.32813 14.8284L8.4997 15");
}

.r6t4zeiqh {
  d: path("M13.2939 7.17038L11.9998 12L10.7058 16.8296");
}

</style>
