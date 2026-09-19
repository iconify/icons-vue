<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4x1ekbrd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:done-all" /></template>
<style>
.k4x1ekbrd {
  fill: currentColor;
  d: path("m18 7l-1.41-1.41l-6.34 6.34l1.41 1.41zm4.24-1.41L11.66 16.17L7.48 12l-1.41 1.41L11.66 19l12-12zM.41 13.41L6 19l1.41-1.41L1.83 12z");
}

</style>
