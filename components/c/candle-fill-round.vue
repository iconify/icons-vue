<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpz-ctbea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:candle-fill-round" /></template>
<style>
.bpz-ctbea {
  fill: currentColor;
  d: path("M15.436 10.365A3 3 0 0 1 17 13v6a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-6c0-1.099.598-2.109 1.564-2.635a3.75 3.75 0 0 1-.397-1.698c0-.761.214-1.573.765-2.124c.402-.403.738-.97 1.015-1.464q.65-1.173 1.117-2.43a1 1 0 0 1 1.917.155c.186.928.762 1.67 1.508 2.229q.057.043.107.093c.958.959 1.237 2.227 1.237 3.541a3.75 3.75 0 0 1-.397 1.698");
}

</style>
