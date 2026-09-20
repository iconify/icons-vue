<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":227};
const content = `<path class="cyogo5blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:adobe-icon" /></template>
<style>
.cyogo5blg {
  fill: var(--svg-color--fa0f00, #fa0f00);
  d: path("m128.024 83.527l60.288 143.042h-39.513l-18.038-45.554H86.642zM256 0v226.54L161.353 0zM94.684 0L0 226.54V0z");
}

</style>
