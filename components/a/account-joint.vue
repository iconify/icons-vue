<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq0d53bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-joint" /></template>
<style>
.eq0d53bvc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 8a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm8 0a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0ZM3 20c.3-3.2 2.3-5 5-5s4 1 4 1s1.3-1 4-1s4.7 1.8 5 5");
}

</style>
