<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zup1egb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clover-16-filled" /></template>
<style>
.zup1egb1x {
  fill: currentColor;
  d: path("M11 1a3 3 0 1 1 0 6H8.5a.5.5 0 0 1-.5-.5V4a3 3 0 0 1 3-3m-7 .02a3 3 0 1 0 0 6h2.5a.5.5 0 0 0 .5-.5v-2.5a3 3 0 0 0-3-3M4 14a3 3 0 1 1 0-6h2.5a.5.5 0 0 1 .5.5V11a3 3 0 0 1-3 3m7 0a3 3 0 1 0 0-6H8.5a.5.5 0 0 0-.5.5V11a3 3 0 0 0 3 3");
}

</style>
