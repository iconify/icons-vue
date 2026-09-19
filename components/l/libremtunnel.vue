<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fwyq2mn1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:libremtunnel" /></template>
<style>
.fwyq2mn1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.77 37.7v5.8h-3.9v-5.78a13.88 13.88 0 0 0-27.76 0v5.78h-3.9V22.27a17.77 17.77 0 1 1 35.53 0Z");
}

</style>
