<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="w24z9kzez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-left-up-light" /></template>
<style>
.w24z9kzez {
  fill: currentColor;
  d: path("M206 224a6 6 0 0 1-6 6A102.12 102.12 0 0 1 98 128V46.49L60.24 84.24a6 6 0 0 1-8.48-8.48l48-48a6 6 0 0 1 8.48 0l48 48a6 6 0 1 1-8.48 8.48L110 46.49V128a90.1 90.1 0 0 0 90 90a6 6 0 0 1 6 6");
}

</style>
