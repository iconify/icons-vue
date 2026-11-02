<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1ner8buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-fill-sharp" /></template>
<style>
.d1ner8buq {
  fill: currentColor;
  d: path("m9 8.586l5.293-5.293a1 1 0 0 1 1.414 0l6 6a1 1 0 0 1 0 1.414L16.414 16Zm-6.707 8.121a1 1 0 0 1 0-1.414L7.586 10L15 17.414L13.414 19H21a1 1 0 0 1 0 2H7a1 1 0 0 1-.707-.293Z");
}

</style>
