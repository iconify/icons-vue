<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sk3gfhbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-revenue" /></template>
<style>
.sk3gfhbch {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 3.5h13V8h-13Zm10.7 9H2.5V8h13v2.9m-2 6.1H5v-4.5h10.2m-1.4 9H3V17h10.5m6.25-.75C19.5 15.5 18.9 15 18 15c-1.05 0-1.75.6-1.75 1.5c0 1.6 3.5.9 3.5 3c0 .9-.75 1.5-1.75 1.5c-.9 0-1.55-.4-1.75-1M18 13.75V15m0 6v1");
}

</style>
