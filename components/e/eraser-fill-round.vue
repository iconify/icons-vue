<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8l-7zvse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-fill-round" /></template>
<style>
.q8l-7zvse {
  fill: currentColor;
  d: path("m9 8.586l2.293-2.293a5.243 5.243 0 0 1 7.414 7.414L16.414 16ZM5.293 19.707a5.243 5.243 0 0 1 0-7.414L7.586 10L15 17.414L13.414 19H21a1 1 0 0 1 0 2H7a1 1 0 0 1-.707-.293Z");
}

</style>
