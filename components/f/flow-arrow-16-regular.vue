<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xc424_bvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-arrow-16-regular" /></template>
<style>
.xc424_bvx {
  fill: currentColor;
  d: path("M3.5 1.5A2 2 0 0 1 5.435 3H11.5a2.5 2.5 0 0 1 0 5h-7a1.5 1.5 0 1 0 0 3h7.793l-1.146-1.146a.5.5 0 1 1 .707-.708l2 2a.5.5 0 0 1 0 .707l-2 2a.5.5 0 1 1-.707-.707L12.293 12H4.5a2.5 2.5 0 0 1 0-5h7a1.5 1.5 0 0 0 0-3H5.435A1.999 1.999 0 0 1 1.5 3.5a2 2 0 0 1 2-2m0 1a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
