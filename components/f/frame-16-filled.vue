<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l7w3_vbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:frame-16-filled" /></template>
<style>
.l7w3_vbip {
  fill: currentColor;
  d: path("M3.5 1a.5.5 0 0 1 .5.5V3h8V1.5a.5.5 0 0 1 1 0V3h1.5a.5.5 0 0 1 0 1H13v8h1.5a.5.5 0 0 1 0 1H13v1.5a.5.5 0 0 1-1 0V13H4v1.5a.5.5 0 0 1-1 0V13H1.5a.5.5 0 0 1 0-1H3V4H1.5a.5.5 0 0 1 0-1H3V1.5a.5.5 0 0 1 .5-.5");
}

</style>
