<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wxqs_e-zq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:inking-tool-accent-16-filled" /></template>
<style>
.wxqs_e-zq {
  fill: currentColor;
  d: path("M14.5 2v2a.5.5 0 0 1-.5.5H2a.5.5 0 0 1-.5-.5V2zm-4 2.5l.52.476l-2.398 4.75a.5.5 0 1 1-.893-.451l2.17-4.3zM9 13c0 .828-.448 1.5-1 1.5s-1-.672-1-1.5s.448-1.5 1-1.5s1 .672 1 1.5");
}

</style>
