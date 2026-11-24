<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae9wrmy0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-warning-fill" /></template>
<style>
.ae9wrmy0p {
  fill: currentColor;
  d: path("M19.707 8.293A1 1 0 0 1 20 9v10a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 7a2 2 0 0 0 2 2h3l-5-5Zm0 5a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0Zm-.99 5H12a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
