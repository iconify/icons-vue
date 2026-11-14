<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dii64bcxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-big-left" /></template>
<style>
.dii64bcxu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m4.826 9.614l4.553-4.553q.794-.795 1.833-.365T12.25 6.25q0 1.5 1.5 1.5h4.125q3.375 0 3.375 3.375v1.75q0 3.375-3.375 3.375H13.75q-1.5 0-1.5 1.5q0 1.124-1.038 1.554t-1.833-.365l-4.553-4.553Q2.44 12 4.826 9.614");
}

</style>
