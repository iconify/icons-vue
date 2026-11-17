<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m8_v_t7ev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:crane-fill-sharp" /></template>
<style>
.m8_v_t7ev {
  fill: currentColor;
  d: path("m2.293 8.293l6-6a1 1 0 0 1 1.221-.15L19.277 8H21a1 1 0 0 1 0 2h-3v2.171A3 3 0 1 1 14 15a1 1 0 0 1 2 0a1.001 1.001 0 0 0 2 0a1 1 0 0 0-1-1a1 1 0 0 1-1-1v-3h-6v10h2a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2h2V10H3a1.002 1.002 0 0 1-.707-1.707M10 8h5.39L10 4.766ZM8 8V5.414L5.414 8Z");
}

</style>
