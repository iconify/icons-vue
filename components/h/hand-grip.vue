<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hsyn7us7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hand-grip" /></template>
<style>
.hsyn7us7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.25a2.75 2.75 0 1 0 0 5.5a2.75 2.75 0 1 0 0-5.5m-1.75 5L8.9 11.9m4.85-3.65l1.35 3.65m-8.8 1.75l-1.55 4.47q-.52 1.52.99 2.04l.52.18q1.51.52 2.04-.99l1.55-4.47q.52-1.52-.99-2.04l-.52-.18q-1.51-.52-2.04.99m7.85 1.23l1.55 4.47q.53 1.51 2.04.99l.52-.18q1.51-.52.99-2.04l-1.55-4.47q-.53-1.51-2.04-.99l-.52.18q-1.51.52-.99 2.04");
}

</style>
