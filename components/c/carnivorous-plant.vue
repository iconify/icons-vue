<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbuqmvbnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carnivorous-plant" /></template>
<style>
.vbuqmvbnt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 14c-6 1.5-9.5-2.5-9.5-7.5c5-.5 9 3 9.5 7.5Zm0 0c6 1.5 9.5-2.5 9.5-7.5c-5-.5-9 3-9.5 7.5Zm0 0v6.5M5.5 6.75l-.25-3m3.5 4.5L9.5 5.5m9 1.25l.25-3m-3.5 4.5L14.5 5.5");
}

</style>
