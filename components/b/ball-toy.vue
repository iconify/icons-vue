<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z6bg7jtav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ball-toy" /></template>
<style>
.z6bg7jtav {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m11.969 15.542q.02.071.026.145q.007.073-.002.147q-.008.073-.031.143q-.023.071-.058.135t-.084.121q-.048.056-.106.102t-.123.08t-.137.054q-.143.041-.292.024q-.148-.017-.278-.089q-.131-.073-.223-.19q-.093-.117-.134-.26Q12.403 10.641 3.345 8.734q-.145-.031-.269-.115q-.123-.084-.204-.209q-.082-.125-.109-.272q-.028-.147.003-.293q.015-.072.044-.14t.071-.129t.095-.112t.114-.092t.131-.068q.068-.028.141-.041t.146-.013t.147.016q9.942 2.093 13.066 13.028");
}

</style>
