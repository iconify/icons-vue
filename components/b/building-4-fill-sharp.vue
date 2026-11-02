<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_gls1bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-fill-sharp" /></template>
<style>
.c_gls1bmj {
  fill: currentColor;
  d: path("M4 4a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v4h3a1 1 0 0 1 1 1v10h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h1Zm5 5h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2m9 10v-9h-2v9Zm-9-6h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

</style>
