<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ifvz-kj4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:glucose-test-strip" /></template>
<style>
.ifvz-kj4u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m1.99 18.475l8.485-8.485l3.535 3.535l-8.485 8.485ZM17.5 2S21 5.5 21 7.5a3.5 3.5 0 0 1-7 0c0-2 3.5-5.5 3.5-5.5ZM8.354 12.111l3.535 3.535");
}

</style>
