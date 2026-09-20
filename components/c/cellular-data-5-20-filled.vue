<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k22gzjgnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cellular-data-5-20-filled" /></template>
<style>
.k22gzjgnf {
  fill: currentColor;
  d: path("M4.75 12a.75.75 0 0 1 .743.64l.008.11v2.503a.75.75 0 0 1-1.493.11L4 15.254V12.75a.75.75 0 0 1 .75-.75");
}

</style>
