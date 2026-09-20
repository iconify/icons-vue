<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lv_2ulbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:keyboard-arrow-up-rounded" /></template>
<style>
.lv_2ulbrm {
  fill: currentColor;
  d: path("m12 10.108l-4.246 4.246q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354l4.389-4.388q.242-.242.565-.242t.566.242l4.388 4.388q.14.14.15.345q.01.203-.15.363t-.354.16t-.354-.16z");
}

</style>
