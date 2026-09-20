<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m24221hhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:fast-down-button" /></template>
<style>
.m24221hhq {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("m29.01 6.24l31.71 54.92H29.01L64 121.76l34.99-60.6H67.28L98.99 6.24z");
}

</style>
