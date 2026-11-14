<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffp--xbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:engine" /></template>
<style>
.ffp--xbag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 8h7.529a1.5 1.5 0 0 1 1.171.563l1.1 1.374a1.5 1.5 0 0 0 1.171.563h.529A1.25 1.25 0 0 1 21 11.75v3A1.25 1.25 0 0 1 19.75 16h-.629a1.5 1.5 0 0 0-1.06.439l-1.622 1.622a1.5 1.5 0 0 1-1.06.439h-5.258a1.5 1.5 0 0 1-1.06-.439l-1.622-1.622A1.5 1.5 0 0 0 6.379 16H5.75a1.25 1.25 0 0 1-1.25-1.25v-3a1.25 1.25 0 0 1 1.25-1.25A1.25 1.25 0 0 0 7 9.25A1.25 1.25 0 0 1 8.25 8M9.5 5h5M12 5v3m-9.5 3v4.5");
}

</style>
