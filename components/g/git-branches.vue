<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0u0m8bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:git-branches" /></template>
<style>
.j0u0m8bky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 2.5V16m-2.5 2.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2.5-9c0-3 4-4.5 9.5-4.5m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0ZM6 9.5c0 2.5 4 4 9.5 4m0 0a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

</style>
