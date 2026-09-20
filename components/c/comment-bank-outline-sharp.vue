<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as_lewtun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:comment-bank-outline-sharp" /></template>
<style>
.as_lewtun {
  fill: currentColor;
  d: path("M13.385 10.116V4H4v13.644L5.65 16H20V4h-2.616v6.116l-2-1.193zM3 20.077V3h18v14H6.077zM4 4v13.385z");
}

</style>
