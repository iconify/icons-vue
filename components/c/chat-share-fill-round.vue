<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zadwgrkjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-share-fill-round" /></template>
<style>
.zadwgrkjl {
  fill: currentColor;
  d: path("M9 18c-.749 0-1.737.152-2.293.707l-1 1a1.71 1.71 0 0 1-1.498.485c-.461-.078-.866-.328-1.193-.655a3.4 3.4 0 0 1-.732-1.116A3.7 3.7 0 0 1 2 17V7a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v6a5 5 0 0 1-5 5Zm7.707-8.707l-3-3a.999.999 0 1 0-1.414 1.414L13.586 9H11a3.98 3.98 0 0 0-2.828 1.172A3.98 3.98 0 0 0 7 13a1 1 0 0 0 2 0a2 2 0 0 1 2-2h2.586l-1.293 1.293a.999.999 0 1 0 1.414 1.414l3-3a1 1 0 0 0 0-1.414");
}

</style>
