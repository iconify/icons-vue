<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vpi3s38zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-minus-corner-fill-sharp" /></template>
<style>
.vpi3s38zr {
  fill: currentColor;
  d: path("M20 9H9v11a1 1 0 0 1-.804.981l-5 1a1 1 0 0 1-1.177-1.177l.935-4.673a9.943 9.943 0 0 1 17.94-8.578A1 1 0 0 1 20 9m-7 6h8a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2");
}

</style>
