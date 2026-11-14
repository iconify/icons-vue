<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="htg4ci77e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:community-hub" /></template>
<style>
.htg4ci77e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.935 9.143Q2.75 10.154 2.75 11.711v6.164q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-6.164q0-1.557-1.185-2.568L14.19 4.132q-2.19-1.866-4.38 0zM9 10.25h6q2.25 0 2.25 2.25v2q0 2.25-2.25 2.25h-3.655l-1.276 1.488q-.048.056-.106.102t-.124.079t-.137.053t-.144.026q-.074.005-.147-.003q-.074-.009-.144-.032t-.135-.059t-.12-.085q-.125-.106-.193-.256q-.069-.149-.069-.313v-1.007q-2-.122-2-2.243v-2q0-2.25 2.25-2.25");
}

</style>
