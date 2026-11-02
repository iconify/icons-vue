<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f4l39xbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barcode-fill-round" /></template>
<style>
.f4l39xbyv {
  fill: currentColor;
  d: path("M5 5v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m4 0v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m4 0v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m4 0v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0m4 0v14a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0");
}

</style>
