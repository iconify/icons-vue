<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lpngq9lcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-upward-alt-rounded" /></template>
<style>
.lpngq9lcj {
  fill: currentColor;
  d: path("m11.5 7.416l-3.746 3.746q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354l4.389-4.388q.242-.243.565-.243t.566.243l4.388 4.388q.14.14.15.344t-.15.364t-.354.16t-.354-.16L12.5 7.416v9.392q0 .213-.143.357t-.357.143t-.357-.144t-.143-.356z");
}

</style>
