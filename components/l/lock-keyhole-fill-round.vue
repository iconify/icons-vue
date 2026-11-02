<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxcgtx9qc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-keyhole-fill-round" /></template>
<style>
.oxcgtx9qc {
  fill: currentColor;
  d: path("M16 9a5 5 0 0 1 5 5v3a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 22H8a5 5 0 0 1-5-5v-3a5 5 0 0 1 5-5V6a4 4 0 0 1 8 0Zm-2 0V6a2 2 0 1 0-4 0v3Zm-3 6.733V18a1 1 0 0 0 2 0v-2.267a2.001 2.001 0 1 0-2 0");
}

</style>
