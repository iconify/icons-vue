<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knlp2pb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blu-ray-disc" /></template>
<style>
.knlp2pb5u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M6.75 12q0-2.175 1.538-3.712Q9.825 6.75 12 6.75t3.712 1.538Q17.25 9.825 17.25 12t-1.538 3.712Q14.175 17.25 12 17.25t-3.712-1.538Q6.75 14.175 6.75 12m-2.033 2.65q-.025-.069-.036-.142q-.012-.073-.008-.147q.003-.074.02-.145q.018-.072.049-.139t.075-.127q.044-.059.098-.109t.118-.088q.063-.039.133-.064q.14-.051.289-.044t.284.069t.236.173t.152.251q.997 2.738 3.735 3.735q.07.025.133.064q.063.038.118.088t.098.109t.075.127t.048.139q.018.071.021.145t-.008.147t-.036.142q-.051.141-.152.251t-.236.173t-.284.069t-.289-.044q-3.397-1.236-4.633-4.633");
}

</style>
