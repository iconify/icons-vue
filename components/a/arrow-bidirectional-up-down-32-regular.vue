<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jdyoozd_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-bidirectional-up-down-32-regular" /></template>
<style>
.jdyoozd_h {
  fill: currentColor;
  d: path("M15.293 3.293a1 1 0 0 1 1.414 0l7 7a1 1 0 1 1-1.414 1.414L17 6.414v19.172l5.293-5.293a1 1 0 0 1 1.414 1.414l-7 7a1 1 0 0 1-1.414 0l-7-7a1 1 0 1 1 1.414-1.414L15 25.586V6.414l-5.293 5.293a1 1 0 1 1-1.414-1.414z");
}

</style>
