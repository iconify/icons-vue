<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guug22ffc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bbq-sauce" /></template>
<style>
.guug22ffc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.462 21.5H3.5v-9c0-2 3-3 3-5v-2h3v2c0 2 3 3 3 5v2.838M5.5 2.5h5v3h-5Zm.5 13h4m8-2c.5 1.75 3.5 2.75 3.5 5a3.5 3.5 0 0 1-7 0c0-1.5.75-2.5 1.75-3.25c0 1 .5 1.75 1 2q0-2.25.75-3.75Z");
}

</style>
