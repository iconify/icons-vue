<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5-6w1bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:aircraft-jack" /></template>
<style>
.o5-6w1bot {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 21.5l5.5-6h6l5.5 6M12 6za1.75 1.75 0 0 1 1.75 1.75v6A1.75 1.75 0 0 1 12 15.5a1.75 1.75 0 0 1-1.75-1.75v-6A1.75 1.75 0 0 1 12 6m0-2.5V6M7.5 3.5h9");
}

</style>
