<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z_6o32b9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-up-down-20-filled" /></template>
<style>
.z_6o32b9m {
  fill: currentColor;
  d: path("M16.447 16.53a.75.75 0 0 1-1.031.392l-5.001-2.5a.75.75 0 1 1 .67-1.342l3.245 1.62l-4.32-9.818l-4.57 10.663a.75.75 0 1 1-1.378-.59L8.857 3.762c.431-1.004 1.853-1.011 2.293-.01l4.606 10.466l1.298-3.247a.75.75 0 0 1 1.392.557z");
}

</style>
