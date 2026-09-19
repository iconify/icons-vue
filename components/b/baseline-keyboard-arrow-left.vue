<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vg6h2rd1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-keyboard-arrow-left" /></template>
<style>
.vg6h2rd1o {
  fill: currentColor;
  d: path("M15.41 16.59L10.83 12l4.58-4.59L14 6l-6 6l6 6z");
}

</style>
