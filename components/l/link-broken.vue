<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ex42gycrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:link-broken" /></template>
<style>
.ex42gycrq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9 7.5H7.5a4.5 4.5 0 0 0 0 9H9m6-9h1.5a4.5 4.5 0 0 1 0 9H15M12 3v2.5m0 13V21M8.5 3.5L9.25 5m6.25 15.5l-.75-1.5");
}

</style>
