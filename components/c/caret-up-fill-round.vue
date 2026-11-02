<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="osy3mqf7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:caret-up-fill-round" /></template>
<style>
.osy3mqf7d {
  fill: currentColor;
  d: path("M11.293 9.293a1 1 0 0 1 1.414 0l4 4A1 1 0 0 1 16 15H8a1.002 1.002 0 0 1-.707-1.707Z");
}

</style>
