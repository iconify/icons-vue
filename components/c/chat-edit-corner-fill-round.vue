<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw1xdg66b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-edit-corner-fill-round" /></template>
<style>
.tw1xdg66b {
  fill: currentColor;
  d: path("M10 13v4a1 1 0 0 1-1 1c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v2a1 1 0 0 1-1 1h-8a3 3 0 0 0-3 3m2 8v-3c0-.265.105-.52.293-.707l5-5a1 1 0 0 1 1.414 0l3 3a1 1 0 0 1 0 1.414l-5 5A1 1 0 0 1 16 22h-3a1 1 0 0 1-1-1");
}

</style>
