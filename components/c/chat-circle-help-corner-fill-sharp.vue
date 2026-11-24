<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9jb-ab5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-help-corner-fill-sharp" /></template>
<style>
.h9jb-ab5y {
  fill: currentColor;
  d: path("M20 9H9v11a1 1 0 0 1-.804.981l-5 1a1 1 0 0 1-1.177-1.177l.935-4.673a9.943 9.943 0 0 1 17.94-8.578A1 1 0 0 1 20 9m-6 7a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 16 16a1 1 0 0 1-2 0m3 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
