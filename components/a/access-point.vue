<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqe_rabgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:access-point" /></template>
<style>
.lqe_rabgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 14.5h16V20H4Zm5.172-5.328a4 4 0 0 1 5.656 0M6.343 6.343a8 8 0 0 1 11.314 0M7.5 17.25h.01");
}

</style>
