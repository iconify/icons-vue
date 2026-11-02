<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hgojwzbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layer-fill-round" /></template>
<style>
.hgojwzbae {
  fill: currentColor;
  d: path("m7.553 7.106l4-2a1 1 0 0 1 .894 0l6 3a2.116 2.116 0 0 1 0 3.788l-6 3a1 1 0 0 1-.894 0l-6-3a2.116 2.116 0 0 1 0-3.788ZM12 16.882l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788Z");
}

</style>
