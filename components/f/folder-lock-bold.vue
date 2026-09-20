<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="os_9m7m6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-lock-bold" /></template>
<style>
.os_9m7m6a {
  fill: currentColor;
  d: path("M224 152h-4v-4a32 32 0 0 0-64 0v4h-4a12 12 0 0 0-12 12v44a12 12 0 0 0 12 12h72a12 12 0 0 0 12-12v-44a12 12 0 0 0-12-12m-44-4a8 8 0 0 1 16 0v4h-16Zm32 48h-48v-20h48Zm4-128h-82.61l-26-29.29a20 20 0 0 0-15-6.71H40a20 20 0 0 0-20 20v148.62A19.41 19.41 0 0 0 39.38 220h65.18a12 12 0 0 0 0-24H44V92h168a12 12 0 0 0 24 0v-4a20 20 0 0 0-20-20M44 68V56h46.61l10.67 12Z");
}

</style>
