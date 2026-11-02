<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="anqgv2bxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:joystick-fill-sharp" /></template>
<style>
.anqgv2bxd {
  fill: currentColor;
  d: path("M13 9.874V14h8a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h3v-1a1 1 0 0 1 2 0v1h3V9.874a4 4 0 1 1 2 0");
}

</style>
