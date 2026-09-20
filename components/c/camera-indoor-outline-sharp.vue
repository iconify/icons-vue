<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g2m44yb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:camera-indoor-outline-sharp" /></template>
<style>
.g2m44yb1y {
  fill: currentColor;
  d: path("M8 17h6v-2l2 1.05v-4.1L14 13v-2H8zm-4 4V9l8-6l8 6v12zm2-2h12v-9l-6-4.5L6 10zm6-6.75");
}

</style>
