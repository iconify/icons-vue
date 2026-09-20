<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="hf2zb4eiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:app-recent-20-regular" /></template>
<style>
.hf2zb4eiv {
  fill: currentColor;
  d: path("M7 2a2 2 0 0 0-2 2H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h1a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2h1a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2h-1a2 2 0 0 0-2-2zm8 3h1a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-1zM5 15H4a1 1 0 0 1-1-1V6a1 1 0 0 1 1-1h1zM6 4a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H7a1 1 0 0 1-1-1z");
}

</style>
