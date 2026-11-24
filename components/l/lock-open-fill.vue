<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yb0n4lbhh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-open-fill" /></template>
<style>
.yb0n4lbhh {
  fill: currentColor;
  d: path("M9 7v1h9a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3v-8a3 3 0 0 1 3-3h1V7a5 5 0 0 1 9.33-2.5a1 1 0 0 1-1.732 1A3 3 0 0 0 9 7m1.158 7.221a2 2 0 1 0 3.684 1.558a2 2 0 0 0-3.684-1.558");
}

</style>
