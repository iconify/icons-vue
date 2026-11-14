<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6oub7r0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-detached" /></template>
<style>
.q6oub7r0i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 2.5V11m-3 3a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm3 3v4.5m4.75-11l2.5-1.5m1.75-3.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

</style>
