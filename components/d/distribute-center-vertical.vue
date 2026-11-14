<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="difk6kbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:distribute-center-vertical" /></template>
<style>
.difk6kbpf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 3.5v6H6v-6ZM15.5 14v6.5h-7V14Zm6-7.5H18m-12 0H2.5m19 10.75h-6m-7 0h-6");
}

</style>
