<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e2dq83-no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:headphones-fill-sharp" /></template>
<style>
.e2dq83-no {
  fill: currentColor;
  d: path("M19.939 11H21a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1h1.918a6.002 6.002 0 0 0-11.836 0H8a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-7a1 1 0 0 1 1-1h1.061a8.002 8.002 0 0 1 15.878 0");
}

</style>
