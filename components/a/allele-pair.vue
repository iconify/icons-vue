<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjz1klbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:allele-pair" /></template>
<style>
.vjz1klbdb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 3.25Q4.75 3.25 4.75 6v4.5q0 .227.126.416L5.599 12l-.723 1.084q-.126.189-.126.416V18q0 2.75 2.75 2.75T10.25 18v-4.5q0-.227-.126-.416L9.401 12l.723-1.084q.126-.189.126-.416V6q0-2.75-2.75-2.75M13.75 6q0-2.75 2.75-2.75T19.25 6v4.5q0 .227-.126.416L18.401 12l.723 1.084q.126.189.126.416V18q0 2.75-2.75 2.75T13.75 18v-4.5q0-.227.126-.416L14.599 12l-.723-1.084q-.126-.189-.126-.416z");
}

</style>
