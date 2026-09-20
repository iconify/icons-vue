<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z4muxl13i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:bed-20-filled" /></template>
<style>
.z4muxl13i {
  fill: currentColor;
  d: path("M15.5 9a2.5 2.5 0 0 1 2.495 2.336L18 11.5v5a.5.5 0 0 1-.992.09L17 16.5V14H3v2.5a.5.5 0 0 1-.992.09L2 16.5v-5a2.5 2.5 0 0 1 2.336-2.495L4.5 9zm-9-6h7a2.5 2.5 0 0 1 2.495 2.336L16 5.5V8h-2v-.5a.5.5 0 0 0-.41-.492L13.5 7H11a.5.5 0 0 0-.492.41l-.008.09V8h-1v-.5a.5.5 0 0 0-.41-.492L9 7H6.5a.5.5 0 0 0-.492.41L6 7.5V8H4V5.5a2.5 2.5 0 0 1 2.336-2.495z");
}

</style>
