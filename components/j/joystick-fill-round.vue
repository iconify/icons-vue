<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr28d1ttx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:joystick-fill-round" /></template>
<style>
.cr28d1ttx {
  fill: currentColor;
  d: path("M13 9.874V14h5a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8v-1a1 1 0 0 1 2 0v1h3V9.874a4 4 0 1 1 2 0");
}

</style>
