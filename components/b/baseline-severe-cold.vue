<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s_kdc9bhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-severe-cold" /></template>
<style>
.s_kdc9bhw {
  fill: currentColor;
  d: path("m12 10.41l4-4L14.59 5L12 7.59V4h-2v3.59L7.41 5L6 6.41l4 4V12H8.41l-4-4L3 9.41L5.59 12H2v2h3.59L3 16.59L4.41 18l4-4H10v1.59l-4 4L7.41 21L10 18.41V22h2v-3.59L14.59 21L16 19.59l-4-4V14h1.59l4 4L19 16.59L16.41 14H20v-2h-8zM19 2h2v5h-2zm0 6h2v2h-2z");
}

</style>
