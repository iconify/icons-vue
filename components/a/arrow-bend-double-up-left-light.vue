<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eluc2_bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-double-up-left-light" /></template>
<style>
.eluc2_bbu {
  fill: currentColor;
  d: path("M84.24 147.76a6 6 0 1 1-8.48 8.48l-48-48a6 6 0 0 1 0-8.48l48-48a6 6 0 0 1 8.48 8.48L40.49 104ZM128 98H94.49l37.75-37.76a6 6 0 0 0-8.48-8.48l-48 48a6 6 0 0 0 0 8.48l48 48a6 6 0 0 0 8.48-8.48L94.49 110H128a90.1 90.1 0 0 1 90 90a6 6 0 0 0 12 0A102.12 102.12 0 0 0 128 98");
}

</style>
