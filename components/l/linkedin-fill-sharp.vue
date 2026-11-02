<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qfk9wvb1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linkedin-fill-sharp" /></template>
<style>
.qfk9wvb1r {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m3 5a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2Zm1 4a1 1 0 0 0-2 0v5a1 1 0 0 0 2 0Zm2 2v3a1 1 0 0 0 2 0v-3a1 1 0 0 1 2 0v3a1 1 0 0 0 2 0v-3a3 3 0 1 0-6 0");
}

</style>
