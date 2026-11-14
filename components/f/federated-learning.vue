<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ac_tp4bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:federated-learning" /></template>
<style>
.ac_tp4bky {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 12.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m1-10h2.5A1.75 1.75 0 0 1 15 4.25v1A1.75 1.75 0 0 1 13.25 7h-2.5A1.75 1.75 0 0 1 9 5.25v-1a1.75 1.75 0 0 1 1.75-1.75m-6.5 14h2.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 6.75 21h-2.5a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75m13 0h2.5a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 19.75 21h-2.5a1.75 1.75 0 0 1-1.75-1.75v-1a1.75 1.75 0 0 1 1.75-1.75M12 10.25V7m-1.75 6.75L7 16.5m6.75-2.75L17 16.5");
}

</style>
