<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r904akbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-letter-spacing-wider" /></template>
<style>
.r904akbfl {
  fill: currentColor;
  d: path("M2 20V4h2v16zm18 0V4h2v16zM7.35 17L11.1 7h1.8l3.75 10h-1.725l-.9-2.55h-4.05l-.9 2.55zm3.15-4h3l-1.45-4.15h-.1z");
}

</style>
