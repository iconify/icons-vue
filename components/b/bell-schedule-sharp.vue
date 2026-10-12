<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_u1l1b3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bell-schedule-sharp" /></template>
<style>
.f_u1l1b3t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 7.25a6 6 0 0 0-6 6v2.58l-.8.72l-.4.35l-2.004 1.85h18.408L19.2 16.9l-.4-.35l-.8-.72v-2.58a6 6 0 0 0-6-6Zm0-4.5v4.5m-1.25 14h2.5");
}

</style>
