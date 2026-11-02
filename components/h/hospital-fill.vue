<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3up1lbmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hospital-fill" /></template>
<style>
.s3up1lbmz {
  fill: currentColor;
  d: path("M20 5v15h1a1 1 0 0 1 0 2h-6v-3a3 3 0 1 0-6 0v3H3a1 1 0 0 1 0-2h1V5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3m-7 2a1 1 0 0 0-2 0v2H9a1 1 0 0 0 0 2h2v2a1 1 0 0 0 2 0v-2h2a1 1 0 0 0 0-2h-2Zm0 15h-2v-3a1 1 0 0 1 2 0Z");
}

</style>
