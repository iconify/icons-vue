<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n6wn-v-sl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cough" /></template>
<style>
.n6wn-v-sl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 17.75V14.5C5 13 4 11 4 9c0-3.5 2.75-6 6-6s5.75 2 5.75 5.25L17 11c0 .472-.223.944-.668.995M15.25 21.5c-1.25 0-1.5-1.75-.25-2c0-1.75 2-2.5 3-1.25c.75-1.5 3.25-1.25 3.25.75c.75.25.75 2.5-.5 2.5Zm-.75-5.75h.01m2.74-1h.01");
}

</style>
