<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6pe25bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:drill-fill-sharp" /></template>
<style>
.b6pe25bjv {
  fill: currentColor;
  d: path("M15 3a1 1 0 0 1 1 1h2a1 1 0 0 1 1 1v1h2a1 1 0 0 1 0 2h-2v1a1 1 0 0 1-1 1h-2a1 1 0 0 1-1 1h-3v4h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h1v-4H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1Z");
}

</style>
