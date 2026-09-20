<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="sdd5wri6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:finn-the-human-fill" /></template>
<style>
.sdd5wri6j {
  fill: currentColor;
  d: path("M176 148a12 12 0 1 1-12-12a12 12 0 0 1 12 12m-84-12a12 12 0 1 0 12 12a12 12 0 0 0-12-12m148-64v80a72.08 72.08 0 0 1-72 72H88a72.08 72.08 0 0 1-72-72V72a32 32 0 0 1 63-8h98a32 32 0 0 1 63 8m-40 72a32 32 0 0 0-32-32H88a32 32 0 0 0-32 32v8a32 32 0 0 0 32 32h80a32 32 0 0 0 32-32Z");
}

</style>
