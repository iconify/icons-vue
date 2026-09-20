<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="d0vvnrpxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chevron-circle-right-12-filled" /></template>
<style>
.d0vvnrpxj {
  fill: currentColor;
  d: path("M1 6a5 5 0 1 1 10 0A5 5 0 0 1 1 6m4.854-1.854a.5.5 0 1 0-.708.708L6.293 6L5.146 7.146a.5.5 0 1 0 .708.708l1.5-1.5a.5.5 0 0 0 0-.708z");
}

</style>
