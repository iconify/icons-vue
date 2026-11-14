<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chpd75bgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:layout-list" /></template>
<style>
.chpd75bgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.125 4h.75A2.625 2.625 0 0 1 9.5 6.625v.75A2.625 2.625 0 0 1 6.875 10h-.75A2.625 2.625 0 0 1 3.5 7.375v-.75A2.625 2.625 0 0 1 6.125 4m0 10h.75A2.625 2.625 0 0 1 9.5 16.625v.75A2.625 2.625 0 0 1 6.875 20h-.75A2.625 2.625 0 0 1 3.5 17.375v-.75A2.625 2.625 0 0 1 6.125 14M12.5 5.5h8m-8 3h5m-5 7h8m-8 3h5");
}

</style>
