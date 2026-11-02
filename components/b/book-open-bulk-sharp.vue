<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vny_iei6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:book-open-bulk-sharp" /></template>
<style>
.vny_iei6b {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.586 18H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-5.586l-2.707 2.707a1 1 0 0 1-1.414 0ZM11 15a1 1 0 0 0 2 0V6a1 1 0 0 0-2 0Z");
}

</style>
