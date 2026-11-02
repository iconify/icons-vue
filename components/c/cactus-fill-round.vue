<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbkhrhzzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cactus-fill-round" /></template>
<style>
.tbkhrhzzl {
  fill: currentColor;
  d: path("M8 14V6a4 4 0 0 1 8 0v5a2 2 0 0 0 2-2V6a1 1 0 0 1 2 0v3a4 4 0 0 1-4 4v7h3a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2h3v-4a4 4 0 0 1-4-4V8a1 1 0 0 1 2 0v4a2 2 0 0 0 2 2");
}

</style>
