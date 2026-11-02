<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6hm1qwau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:loading-fill-sharp" /></template>
<style>
.c6hm1qwau {
  fill: currentColor;
  d: path("M16 10a2 2 0 1 1 3.999-.001A2 2 0 0 1 16 10m-6 2a2 2 0 1 1 3.999-.001A2 2 0 0 1 10 12m-6 2a2 2 0 1 1 3.999-.001A2 2 0 0 1 4 14");
}

</style>
