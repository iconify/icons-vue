<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qei6nsb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:copyleft-fill" /></template>
<style>
.qei6nsb8j {
  fill: currentColor;
  d: path("M128 56a72 72 0 1 0 72 72a72.08 72.08 0 0 0-72-72m0 120a47.66 47.66 0 0 1-38.4-19.19a8 8 0 0 1 12.8-9.61a32 32 0 1 0 0-38.4a8 8 0 0 1-12.8-9.61A48 48 0 1 1 128 176m0-152a104 104 0 1 0 104 104A104 104 0 0 0 128 24m0 192a88 88 0 1 1 88-88a88.1 88.1 0 0 1-88 88");
}

</style>
