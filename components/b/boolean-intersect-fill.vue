<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mi4xbacxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-fill" /></template>
<style>
.mi4xbacxe {
  fill: currentColor;
  d: path("M2 4a2 2 0 0 1 2-2h3a1 1 0 0 1 0 2H4v3a1 1 0 0 1-2 0Zm12-2a2 2 0 0 1 2 2v1a1 1 0 0 1-2 0V4h-3a1 1 0 0 1 0-2Zm-4 6h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2v-4a2 2 0 0 1 2-2m10 0a2 2 0 0 1 2 2v3a1 1 0 0 1-2 0v-3h-1a1 1 0 0 1 0-2ZM5 14a1 1 0 0 1 0 2H4a2 2 0 0 1-2-2v-3a1 1 0 0 1 2 0v3Zm17 6a2 2 0 0 1-2 2h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0Zm-9 0a1 1 0 0 1 0 2h-3a2 2 0 0 1-2-2v-1a1 1 0 0 1 2 0v1Z");
}

</style>
