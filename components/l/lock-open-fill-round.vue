<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ssfjwif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-fill-round" /></template>
<style>
.p2ssfjwif {
  fill: currentColor;
  d: path("M8 9V6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 0 0-3.843-.778A2 2 0 0 0 10 6v3h6a5 5 0 0 1 5 5v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-3a5 5 0 0 1 5-5");
}

</style>
