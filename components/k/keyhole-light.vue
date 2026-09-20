<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="z1j_8abit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:keyhole-light" /></template>
<style>
.z1j_8abit {
  fill: currentColor;
  d: path("M128 26a102 102 0 1 0 102 102A102.12 102.12 0 0 0 128 26m0 192a90 90 0 1 1 90-90a90.1 90.1 0 0 1-90 90m38-106a38 38 0 1 0-61.5 29.86l-14 31.72A6 6 0 0 0 96 182h64a6 6 0 0 0 5.49-8.42l-14-31.72A38.16 38.16 0 0 0 166 112m-25 22.53a6 6 0 0 0-2.49 7.61L150.8 170h-45.6l12.29-27.86a6 6 0 0 0-2.49-7.61a26 26 0 1 1 26 0");
}

</style>
