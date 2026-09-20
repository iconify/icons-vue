<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh7lg0bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-swap-24-filled" /></template>
<style>
.kh7lg0bxs {
  fill: currentColor;
  d: path("M6.08 9.02a6.001 6.001 0 0 1 11.84 0a4.5 4.5 0 0 1 3.75 6.175l-1.683-1.682a1.75 1.75 0 0 0-2.819 1.987h-2.336a1.75 1.75 0 0 0-2.82-1.987l-2.5 2.5A1.75 1.75 0 0 0 9.169 18H6.5a4.5 4.5 0 0 1-.42-8.98m7.7 6.26a.75.75 0 1 0-1.06-1.06l-2.5 2.5a.75.75 0 0 0 0 1.06l2.5 2.5a.75.75 0 1 0 1.06-1.06L12.56 18h6.88l-1.22 1.22a.75.75 0 1 0 1.06 1.06l2.5-2.5a.75.75 0 0 0 0-1.06l-2.5-2.5a.75.75 0 1 0-1.06 1.06l1.22 1.22h-6.88z");
}

</style>
