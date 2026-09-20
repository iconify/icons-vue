<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hmdwdacnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-elbow-down-right-thin" /></template>
<style>
.hmdwdacnq {
  fill: currentColor;
  d: path("m218.83 178.83l-48 48a4 4 0 0 1-5.66-5.66L206.34 180H72a4 4 0 0 1-4-4V32a4 4 0 0 1 8 0v140h130.34l-41.17-41.17a4 4 0 1 1 5.66-5.66l48 48a4 4 0 0 1 0 5.66");
}

</style>
