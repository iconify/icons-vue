<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtsoi3b4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:glass-water-fill" /></template>
<style>
.qtsoi3b4l {
  fill: currentColor;
  d: path("m19.773 5.098l-1.581 14.233A3 3 0 0 1 15.21 22H8.79a3 3 0 0 1-2.982-2.669L4.227 5.098A2.79 2.79 0 0 1 7 2h10a2.79 2.79 0 0 1 2.773 3.098M6.215 4.877L6.895 11h10.21l.68-6.123A.79.79 0 0 0 17 4H7a.79.79 0 0 0-.785.877");
}

</style>
