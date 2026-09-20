<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqvaunpbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:inking-tool-accent-24-filled" /></template>
<style>
.yqvaunpbp {
  fill: currentColor;
  d: path("M4 7h16.25a.25.25 0 0 0 .243-.193l.007-.057V3H3.75v3.75a.25.25 0 0 0 .193.243zm7.976 6.946l2.641-5.947l.883-.499l.758.499l-2.911 6.556a.75.75 0 1 1-1.371-.61M13 19c0 1.105-.448 2-1 2s-1-.895-1-2s.448-2 1-2s1 .895 1 2");
}

</style>
