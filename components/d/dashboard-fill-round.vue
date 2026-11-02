<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fmcmv3y4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dashboard-fill-round" /></template>
<style>
.fmcmv3y4h {
  fill: currentColor;
  d: path("M6 3h2a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m10 0h2a3 3 0 1 1 0 6h-2a3 3 0 1 1 0-6m0 8h2a3 3 0 0 1 3 3v4a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3M6 15h2a3 3 0 1 1 0 6H6a3 3 0 1 1 0-6");
}

</style>
