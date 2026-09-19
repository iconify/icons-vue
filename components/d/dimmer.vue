<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dwik-nblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dimmer" /></template>
<style>
.dwik-nblt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  d: path("M24 4.5a13.51 13.51 0 0 0-13.41 13.41c0 8 7.32 11.07 7.32 15.24v1.21h12.18v-1.21c0-4.15 7.32-7.2 7.32-15.24A13.51 13.51 0 0 0 24 4.5Zm-6.09 29.86v4.57h12.18v-4.57Zm0 4.57v4.57h12.18v-4.57Z");
}

</style>
