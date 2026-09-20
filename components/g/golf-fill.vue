<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="k2fk3pt3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:golf-fill" /></template>
<style>
.k2fk3pt3o {
  fill: currentColor;
  d: path("M175.47 197.14a8 8 0 0 1-4.61 10.33a126 126 0 0 1-34.86 8.21V248a8 8 0 0 1-16 0v-32.32a126 126 0 0 1-34.86-8.21a8 8 0 1 1 5.72-14.94C104 197.56 116.15 200 128 200s24-2.44 37.14-7.47a8 8 0 0 1 10.33 4.61M216 96a88 88 0 1 1-88-88a88.1 88.1 0 0 1 88 88m-72 36a12 12 0 1 0-12 12a12 12 0 0 0 12-12m32-32a12 12 0 1 0-12 12a12 12 0 0 0 12-12");
}

</style>
