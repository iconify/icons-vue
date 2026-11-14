<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx-fotivx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:butcher-shop" /></template>
<style>
.xx-fotivx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.625 1.75h8.75q3.375 0 3.375 3.375v5.75q0 1.837-1 2.674v6.201q0 1.036-.732 1.768t-1.768.732q-2.5 0-2.5-2.5v-5.5H7.625q-3.375 0-3.375-3.375v-5.75q0-3.375 3.375-3.375m-1.375 5Q6.25 9 8.5 9t2.25-2.25T8.5 4.5T6.25 6.75m9 7.5v5.5q0 1 1 1q.414 0 .707-.293t.293-.707v-5.566q-.405.066-.875.066z");
}

</style>
