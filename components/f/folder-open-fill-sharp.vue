<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9qq437rh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:folder-open-fill-sharp" /></template>
<style>
.c9qq437rh {
  fill: currentColor;
  d: path("M20 10H8a1 1 0 0 0-.949.684l-1 3a1.001 1.001 0 0 0 1.898.632L8.721 12h13l-2.772 8.316A1 1 0 0 1 18 21H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h7c.265 0 .52.105.707.293L12.414 5H19a1 1 0 0 1 1 1Z");
}

</style>
