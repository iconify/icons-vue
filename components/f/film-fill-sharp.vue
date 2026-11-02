<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfzkbcgox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:film-fill-sharp" /></template>
<style>
.mfzkbcgox {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M6 7V4H4v3Zm14-3h-2v3h2ZM6 11V9H4v2Zm12 0h2V9h-2Zm-3 0H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2m-9 2H4v2h2Zm12 0v2h2v-2ZM4 20h2v-3H4Zm14-3v3h2v-3Z");
}

</style>
