<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="aeynp4blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:alarm-light" /></template>
<style>
.aeynp4blt {
  fill: currentColor;
  d: path("M128 42a94 94 0 1 0 94 94a94.11 94.11 0 0 0-94-94m0 176a82 82 0 1 1 82-82a82.1 82.1 0 0 1-82 82M60.24 36.24l-32 32a6 6 0 1 1-8.48-8.48l32-32a6 6 0 1 1 8.48 8.48m176 32a6 6 0 0 1-8.48 0l-32-32a6 6 0 0 1 8.48-8.48l32 32a6 6 0 0 1 0 8.48M184 130a6 6 0 0 1 0 12h-56a6 6 0 0 1-6-6V80a6 6 0 0 1 12 0v50Z");
}

</style>
