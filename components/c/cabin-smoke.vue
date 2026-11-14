<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tuimtmmhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cabin-smoke" /></template>
<style>
.tuimtmmhi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 11za4.5 4.5 0 0 1 4.5 4.5V17a4.5 4.5 0 0 1-4.5 4.5A4.5 4.5 0 0 1 7.5 17v-1.5A4.5 4.5 0 0 1 12 11M8 8Q6.5 6.5 8 5.25T8 2.5M12 8q-1.5-1.5 0-2.75t0-2.75M16 8q-1.5-1.5 0-2.75t0-2.75m-5.75 12h3.5");
}

</style>
