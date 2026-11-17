<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjmmmrbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuse-fill" /></template>
<style>
.sjmmmrbwi {
  fill: currentColor;
  d: path("M18 2a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2v10a2 2 0 0 1 2 2v1a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2v-1a2 2 0 0 1 2-2V7a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2Zm-4.2 6.6a1 1 0 0 0-1.6-1.2l-3 4A.999.999 0 0 0 10 13h2l-1.8 2.4a1 1 0 0 0 1.6 1.2l3-4A.999.999 0 0 0 14 11h-2Z");
}

</style>
