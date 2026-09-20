<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_y-h6bce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:acria" /></template>
<style>
.g_y-h6bce {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.313 11.156H7.78L12 4.406l5.344 9.563H8.906l-1.969 3.375h1.97l1.687-2.813h2.812l1.688 2.813h2.25l-1.688-2.813h2.25L21 19.594h-7.313L12 16.219l-1.687 3.375H3l4.5-7.875h6.187L12 8.344z");
}

</style>
