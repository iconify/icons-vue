<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ad0u0jetp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:distribute-vertical-fill-round" /></template>
<style>
.ad0u0jetp {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2ZM9 8h6a4 4 0 0 1 0 8H9a4 4 0 0 1 0-8m12 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
