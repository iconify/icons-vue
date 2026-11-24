<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="niij0ab9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-fill" /></template>
<style>
.niij0ab9p {
  fill: currentColor;
  d: path("M7 8V7a5 5 0 0 1 10 0v1h1a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3Zm8-1a3 3 0 1 0-6 0v1h6Zm-4 8.733V17a1 1 0 0 0 2 0v-1.267a2.001 2.001 0 1 0-2 0");
}

</style>
