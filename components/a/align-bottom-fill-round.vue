<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpsctej-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:align-bottom-fill-round" /></template>
<style>
.fpsctej-e {
  fill: currentColor;
  d: path("M11 7v6a4 4 0 0 1-8 0V7a4 4 0 0 1 8 0m10 4v2a4 4 0 0 1-8 0v-2a4 4 0 0 1 8 0m0 8a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
