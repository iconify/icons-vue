<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k7-gfnbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:breach-notification" /></template>
<style>
.k7-gfnbos {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 9.5h2.815a1.75 1.75 0 0 0 .819-.203l5.547-2.937A1.75 1.75 0 0 1 17 7.907v8.186a1.75 1.75 0 0 1-2.569 1.547l-5.547-2.937a1.75 1.75 0 0 0-.819-.203H5.25a1.75 1.75 0 0 1-1.75-1.75v-1.5A1.75 1.75 0 0 1 5.25 9.5m1.75 5L8.5 20M20 9l1.5-1.5m-1 4.5h1.25");
}

</style>
