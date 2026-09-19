<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxnzfwwyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-border-color" /></template>
<style>
.wxnzfwwyy {
  fill: currentColor;
  d: path("M22 24H2v-4h20zM13.06 5.19l3.75 3.75L7.75 18H4v-3.75zm4.82 2.68l-3.75-3.75l1.83-1.83a.996.996 0 0 1 1.41 0l2.34 2.34c.39.39.39 1.02 0 1.41z");
}

</style>
