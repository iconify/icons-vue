<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdkr6jbvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:candle-fill" /></template>
<style>
.kdkr6jbvy {
  fill: currentColor;
  d: path("M15.564 10.081A2 2 0 0 1 17 12v8a2 2 0 0 1-2 2H9a2 2 0 0 1-2-2v-8c0-.887.586-1.669 1.436-1.919c-.439-1.1-.385-2.657.496-3.538c.402-.403.738-.97 1.015-1.464q.65-1.173 1.117-2.43a1 1 0 0 1 1.917.155c.186.928.762 1.67 1.508 2.229q.057.043.107.093c.958.959 1.237 2.227 1.237 3.541c.002.484-.089.964-.269 1.414");
}

</style>
