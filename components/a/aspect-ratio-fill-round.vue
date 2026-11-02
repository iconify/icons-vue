<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gasy4njrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:aspect-ratio-fill-round" /></template>
<style>
.gasy4njrd {
  fill: currentColor;
  d: path("M2 9a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20H7a5 5 0 0 1-5-5Zm4 3a1 1 0 0 0 2 0v-1a.997.997 0 0 1 1-1h1a1 1 0 0 0 0-2H9a3 3 0 0 0-3 3Zm12 0a1 1 0 0 0-2 0v1a.997.997 0 0 1-1 1h-1a1 1 0 0 0 0 2h1a3 3 0 0 0 3-3Z");
}

</style>
