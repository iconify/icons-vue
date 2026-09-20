<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fs68e6bbs"/><path class="nek9o8zpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:infer" /></template>
<style>
.fs68e6bbs {
  fill: var(--svg-color--7d29e4, #7d29e4);
  d: path("M256 128c0 70.693-57.308 128-128 128S0 198.692 0 128S57.308 0 128 0s128 57.308 128 128");
}

.nek9o8zpu {
  fill: var(--svg-color--fff, #fff);
  d: path("M169.888 125.664h-50.092V63.24c0-2.881-1.413-5.217-5.216-5.217c-3.612 0-5.215 2.336-5.215 5.216v130.608c0 2.88 1.413 5.216 5.216 5.216c3.612 0 5.215-2.335 5.215-5.216v-57.752h50.092c2.88 0 5.215-1.412 5.215-5.215c0-3.614-2.335-5.216-5.215-5.216");
}

</style>
