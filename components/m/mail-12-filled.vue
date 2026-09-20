<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="f6g_98bbl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-12-filled" /></template>
<style>
.f6g_98bbl {
  fill: currentColor;
  d: path("M2 5.248V7.5A1.5 1.5 0 0 0 3.5 9h5A1.5 1.5 0 0 0 10 7.5V5.248L6.205 6.956a.5.5 0 0 1-.41 0zm.037-1.08L6 5.952l3.963-1.784A1.5 1.5 0 0 0 8.5 3h-5a1.5 1.5 0 0 0-1.463 1.168");
}

</style>
