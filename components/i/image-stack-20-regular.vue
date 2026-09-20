<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bjyj_0o6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:image-stack-20-regular" /></template>
<style>
.bjyj_0o6i {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v8a3 3 0 0 0 3 3h8a3 3 0 0 0 3-3V6a3 3 0 0 0-3-3zm7.707 13l-2.47-2.47a1.75 1.75 0 0 0-2.474 0L6.293 16H6a2 2 0 0 1-2-2v-4h12v4a2 2 0 0 1-2 2zm-6 0l1.763-1.763a.75.75 0 0 1 1.06 0L12.293 16zM16 9h-2.793l-1.97-1.97a1.75 1.75 0 0 0-2.474 0L6.793 9H4V6a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2zM8.207 9L9.47 7.737a.75.75 0 0 1 1.06 0L11.793 9zM15 6a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-1 7.5a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
