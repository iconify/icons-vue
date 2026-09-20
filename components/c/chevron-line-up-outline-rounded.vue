<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2y2g0bnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chevron-line-up-outline-rounded" /></template>
<style>
.m2y2g0bnn {
  fill: currentColor;
  d: path("M7 7.77q-.213 0-.357-.144T6.5 7.269t.143-.357T7 6.77h10q.214 0 .357.143t.143.357t-.143.357T17 7.77zm5 5.415L7.754 17.43q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354l4.389-4.388q.242-.243.565-.243t.566.242l4.388 4.389q.14.14.15.344t-.15.364t-.354.16t-.354-.16z");
}

</style>
