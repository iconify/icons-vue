<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_yjiabiy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fuse-fill-sharp" /></template>
<style>
.w_yjiabiy {
  fill: currentColor;
  d: path("M19 2a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-1v10h1a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h1V7H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm-5.2 6.6a1 1 0 0 0-1.6-1.2l-3 4A.999.999 0 0 0 10 13h2l-1.8 2.4a1 1 0 0 0 1.6 1.2l3-4A.999.999 0 0 0 14 11h-2Z");
}

</style>
