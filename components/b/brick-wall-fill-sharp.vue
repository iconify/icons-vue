<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qx2ebodon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:brick-wall-fill-sharp" /></template>
<style>
.qx2ebodon {
  fill: currentColor;
  d: path("M11 7H2V4a1 1 0 0 1 1-1h8Zm11 0h-9V3h8a1 1 0 0 1 1 1ZM7 9v2H2V9Zm2 0h6v2H9Zm8 2V9h5v2Zm-6 2v2H2v-2Zm11 0v2h-9v-2ZM7 17v4H3a1 1 0 0 1-1-1v-3Zm8 4H9v-4h6Zm7-4v3a1 1 0 0 1-1 1h-4v-4Z");
}

</style>
