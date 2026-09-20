<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ajjlk6b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:fluent-32-regular" /></template>
<style>
.ajjlk6b2s {
  fill: currentColor;
  d: path("M16.553 2.106a1 1 0 0 1 .894 0l8 4a1 1 0 0 1 0 1.788L19.237 11l6.21 3.106a1 1 0 0 1 0 1.788L18 19.618V29a1 1 0 0 1-1.49.872l-8-4.5A1 1 0 0 1 8 24.5V7a1 1 0 0 1 .553-.894zM10 7.618v16.297l6 3.375V19a1 1 0 0 1 .553-.894L22.763 15l-6.21-3.106a1 1 0 0 1 0-1.788L22.763 7L17 4.118z");
}

</style>
