<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7zjvobyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:backpack-fill-sharp" /></template>
<style>
.t7zjvobyz {
  fill: currentColor;
  d: path("M15 6h5a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V7a1 1 0 0 1 1-1h5V3a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1Zm-2 0V4h-2v2Zm3 4H8a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2m-1 9a1 1 0 0 0 2 0v-3a1 1 0 0 0-1-1H8a1 1 0 0 0-1 1v3a1 1 0 0 0 2 0v-2h6Z");
}

</style>
