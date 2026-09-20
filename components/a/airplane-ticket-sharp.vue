<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ji6x2_z6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:airplane-ticket-sharp" /></template>
<style>
.ji6x2_z6b {
  fill: currentColor;
  d: path("M2 20v-6q.825 0 1.413-.587T4 12t-.587-1.412T2 10V4h20v16zm6.85-4.35l8.9-2.35q.375-.1.563-.463t.087-.737t-.437-.562t-.713-.088l-2.45.65l-4-3.75l-1.4.35l2.4 4.2l-2.4.6l-1.25-.95l-.95.25z");
}

</style>
