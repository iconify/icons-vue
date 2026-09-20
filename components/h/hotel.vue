<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi6cvjbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hotel" /></template>
<style>
.hi6cvjbyr {
  fill: currentColor;
  d: path("M1 19V4h2v10h8V6h8q1.65 0 2.825 1.175T23 10v9h-2v-3H3v3zm3.875-6.875Q4 11.25 4 10t.875-2.125T7 7t2.125.875T10 10t-.875 2.125T7 13t-2.125-.875");
}

</style>
