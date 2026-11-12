<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_067bc0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-edit-fill-sharp" /></template>
<style>
.h_067bc0y {
  fill: currentColor;
  d: path("m13.414 22l-7.707-7.707a1 1 0 0 0-1.414 0L2 16.586V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1Zm3.293-17.707a1 1 0 0 0-1.414 0l-5 5A1 1 0 0 0 10 10v3a1 1 0 0 0 1 1h3c.265 0 .52-.105.707-.293l5-5A1 1 0 0 0 20 8.001v-.002a1 1 0 0 0-.293-.706ZM4 17.414l1-1L10.586 22H3a1 1 0 0 1-1-1v-1.586Z");
}

</style>
