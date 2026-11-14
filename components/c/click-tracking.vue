<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt2ks9x3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:click-tracking" /></template>
<style>
.zt2ks9x3z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.867 4.521l8.891 4.015a1.392 1.392 0 0 1-.133 2.589l-2.645.882a1.5 1.5 0 0 0-.958.978l-.897 2.89a1.335 1.335 0 0 1-2.516.094L4.854 6.437a1.5 1.5 0 0 1 2.013-1.916M16 14.5h1.629a1.5 1.5 0 0 1 1.06.439l2 2a1.5 1.5 0 0 1 0 2.122l-1.628 1.628a1.5 1.5 0 0 1-2.122 0l-2-2a1.5 1.5 0 0 1-.439-1.06V16a1.5 1.5 0 0 1 1.5-1.5m.75 2.25h.01");
}

</style>
