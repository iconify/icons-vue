<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc_d-xvhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-swipe-down-alt" /></template>
<style>
.cc_d-xvhw {
  fill: currentColor;
  d: path("M13 13.9a5 5 0 1 0-2 0v4.27l-1.59-1.59L8 18l4 4l4-4l-1.41-1.41L13 18.17z");
}

</style>
