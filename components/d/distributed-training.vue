<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpvbobcxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:distributed-training" /></template>
<style>
.cpvbobcxg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 2.5l3 1.75v3.5L12 9.5L9 7.75v-3.5ZM9 4.25L12 6l3-1.75M12 6v3.5M5.5 14l3 1.75v3.5L5.5 21l-3-1.75v-3.5Zm-3 1.75l3 1.75l3-1.75m-3 1.75V21m13-7l3 1.75v3.5l-3 1.75l-3-1.75v-3.5Zm-3 1.75l3 1.75l3-1.75m-3 1.75V21m-10-5.25L12 9.5l3.5 6.25m-7 1.75h7");
}

</style>
