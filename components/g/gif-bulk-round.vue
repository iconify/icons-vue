<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmy7llbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gif-bulk-round" /></template>
<style>
.zmy7llbpf {
  fill: currentColor;
  d: path("M5 9c-.449 0-1 .551-1 1v4c0 .449.551 1 1 1h2v-2H6a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H5c-1.556 0-3-1.444-3-3v-4c0-1.556 1.444-3 3-3h3a1 1 0 0 1 0 2Zm6 7V8a1 1 0 0 1 2 0v8a1 1 0 0 1-2 0m6-7v2h3a1 1 0 0 1 0 2h-3v3a1 1 0 0 1-2 0V8a1 1 0 0 1 1-1h5a1 1 0 0 1 0 2Z");
}

</style>
