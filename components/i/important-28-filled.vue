<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="p4c3zmunn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:important-28-filled" /></template>
<style>
.p4c3zmunn {
  fill: currentColor;
  d: path("M14 20a3 3 0 1 1 0 6a3 3 0 0 1 0-6m0-18a5 5 0 0 1 5 5c0 .538-.126 1.257-.304 2.02a40 40 0 0 1-.702 2.551a103 103 0 0 1-1.607 4.765A2.53 2.53 0 0 1 14 18a2.53 2.53 0 0 1-2.387-1.664a103 103 0 0 1-1.607-4.765a40 40 0 0 1-.702-2.55C9.126 8.257 9 7.538 9 7a5 5 0 0 1 5-5");
}

</style>
