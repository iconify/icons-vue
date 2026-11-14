<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k509s29sh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glove-pair-leather" /></template>
<style>
.k509s29sh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 21v-7.5l-1.75-2c-.75-.75.25-2.25 1.25-1.5l.5.5v-5a2 2 0 0 1 2-2h1.5a2 2 0 0 1 2 2V21Zm14 0v-7.5l1.75-2c.75-.75-.25-2.25-1.25-1.5l-.5.5v-5a2 2 0 0 0-2-2h-1.5a2 2 0 0 0-2 2V21ZM7.75 3.5v5m8.5-5v5M5 17.5h5.5m3 0H19");
}

</style>
