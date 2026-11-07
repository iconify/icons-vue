<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjofkbbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-warning-fill-sharp" /></template>
<style>
.zjofkbbuj {
  fill: currentColor;
  d: path("m7.414 18l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1ZM13 10V7a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0m-.99 2H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
