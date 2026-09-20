<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdbwwgwit"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-capslock-outline-rounded" /></template>
<style>
.jdbwwgwit {
  fill: currentColor;
  d: path("M7 17.5q-.213 0-.357-.143T6.5 17t.143-.357T7 16.5h10q.214 0 .357.143T17.5 17t-.143.357T17 17.5zm5-9.792l-4.246 4.246q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354l4.389-4.388q.242-.242.565-.242t.566.242l4.388 4.388q.14.14.15.344t-.15.364t-.354.16t-.354-.16z");
}

</style>
