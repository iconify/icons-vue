<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xe4m55qba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ancestor-portrait" /></template>
<style>
.xe4m55qba {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.875 1.75H6.125q-3.375 0-3.375 3.375v13.75q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375V5.125q0-3.375-3.375-3.375M15 9.75q0 3-3 3t-3-3t3-3t3 3M12 14q3.28 0 4.221 3.294q.02.071.026.145q.007.073-.002.147q-.008.073-.031.143q-.023.071-.058.135t-.084.121q-.048.056-.106.102t-.123.08q-.066.034-.137.054q-.143.041-.292.024q-.148-.017-.278-.089q-.131-.073-.223-.19q-.093-.117-.134-.26Q14.149 15.5 12 15.5t-2.779 2.206q-.041.143-.134.26q-.092.117-.223.19q-.13.072-.278.089t-.292-.024q-.071-.02-.137-.054q-.065-.034-.123-.08t-.106-.102t-.084-.121t-.058-.135t-.031-.143q-.009-.074-.002-.147q.006-.074.026-.145Q8.72 14 12 14");
}

</style>
