<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="m_jlp4bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:align-left-simple-thin" /></template>
<style>
.m_jlp4bfr {
  fill: currentColor;
  d: path("M36 56v144a4 4 0 0 1-8 0V56a4 4 0 0 1 8 0m200 40v64a12 12 0 0 1-12 12H72a12 12 0 0 1-12-12V96a12 12 0 0 1 12-12h152a12 12 0 0 1 12 12m-8 0a4 4 0 0 0-4-4H72a4 4 0 0 0-4 4v64a4 4 0 0 0 4 4h152a4 4 0 0 0 4-4Z");
}

</style>
