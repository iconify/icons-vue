<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0npc1bun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fuel-tank-rocket-sharp" /></template>
<style>
.i0npc1bun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 2.75C10.45 2.75 12 5.25 12 8v13.25H4.5V8c0-2.75 1.55-5.25 3.75-5.25ZM4.5 9H12m0 1.25h3.75M12 16h3.75m1.5-9l1.5 1.35v7.9l1.75 2.5v1.5H14v-1.5l1.75-2.5v-7.9z");
}

</style>
