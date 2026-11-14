<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h3j6adblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:corporate-tax" /></template>
<style>
.h3j6adblh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.1 21.5H4.5v-19h11v10.2M8 7h.25M12 7h.25M8 11h.25M12 11h.25M8 15h.25m6.5 6.25l6.5-6.5m-5.75.75h.01m4.99 5h.01");
}

</style>
