<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-filwbyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-ebooks" /></template>
<style>
.w-filwbyy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.875 1.25h-9.75q-3.375 0-3.375 3.375v14.75q0 1.398.989 2.386q.988.989 2.386.989h9.75q1.398 0 2.386-.989q.989-.988.989-2.386V4.625q0-3.375-3.375-3.375");
}

</style>
