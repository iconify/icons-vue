<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q48-8fbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:command-fill-round" /></template>
<style>
.q48-8fbsc {
  fill: currentColor;
  d: path("M8 10H6a4 4 0 1 1 4-4v2h4V6a4 4 0 1 1 4 4h-2v4h2a4 4 0 1 1-4 4v-2h-4v2a4 4 0 1 1-4-4h2Zm2 4h4v-4h-4Z");
}

</style>
