<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l33rl4bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-fill-sharp" /></template>
<style>
.l33rl4bui {
  fill: currentColor;
  d: path("m17.414 22l-9.707-9.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1ZM15.293 4.293l-4 4A1 1 0 0 0 11 9v2a1 1 0 0 0 1 1h2c.265 0 .52-.105.707-.293l4-4a1 1 0 0 0 0-1.414l-2-2a1 1 0 0 0-1.414 0M4 17.414l3-3L14.586 22H3a1 1 0 0 1-1-1v-1.586Z");
}

</style>
