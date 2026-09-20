<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="p6ugz0t0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:battery-charging-bold" /></template>
<style>
.p6ugz0t0p {
  fill: currentColor;
  d: path("M196 52H28A28 28 0 0 0 0 80v96a28 28 0 0 0 28 28h168a28 28 0 0 0 28-28V80a28 28 0 0 0-28-28m4 124a4 4 0 0 1-4 4H28a4 4 0 0 1-4-4V80a4 4 0 0 1 4-4h168a4 4 0 0 1 4 4Zm56-72v48a12 12 0 0 1-24 0v-48a12 12 0 0 1 24 0m-113.62 18a12 12 0 0 1 0 12l-16 28a12 12 0 1 1-20.84-11.9l5.78-10.1H100a12 12 0 0 1-10.42-18l16-28a12 12 0 0 1 20.84 12l-5.74 10H132a12 12 0 0 1 10.38 6");
}

</style>
