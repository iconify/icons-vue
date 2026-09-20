<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="eividsupk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-bend-double-up-right-fill" /></template>
<style>
.eividsupk {
  fill: currentColor;
  d: path("m229.66 109.66l-48 48a8 8 0 0 1-11.32-11.32L212.69 104l-42.35-42.34a8 8 0 0 1 11.32-11.32l48 48a8 8 0 0 1 0 11.32m-48-11.32l-48-48A8 8 0 0 0 120 56v40.3A104.15 104.15 0 0 0 24 200a8 8 0 0 0 16 0a88.11 88.11 0 0 1 80-87.63V152a8 8 0 0 0 13.66 5.66l48-48a8 8 0 0 0 0-11.32");
}

</style>
