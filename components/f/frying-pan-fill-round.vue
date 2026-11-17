<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsyaiubli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:frying-pan-fill-round" /></template>
<style>
.vsyaiubli {
  fill: currentColor;
  d: path("m14.764 10l5.789-2.894a1 1 0 1 1 .894 1.788L16 11.618V12a5 5 0 0 1-5 5H7a5 5 0 0 1-5-5v-1a1 1 0 0 1 1-1Z");
}

</style>
