<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y1w-a-3zr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cursor-hover-off-16-filled" /></template>
<style>
.y1w-a-3zr {
  fill: currentColor;
  d: path("m12.293 13l1.853 1.854a.5.5 0 0 0 .708-.708l-13-13a.5.5 0 1 0-.708.708l1.242 1.241A2 2 0 0 0 1 5v5a2 2 0 0 0 2 2h4V8.5c0-.228.052-.449.146-.646L8 8.707V14.5a.5.5 0 0 0 .9.3l1.35-1.8zm1.612-1.216A2 2 0 0 0 15 10V5a2 2 0 0 0-2-2H5.121z");
}

</style>
