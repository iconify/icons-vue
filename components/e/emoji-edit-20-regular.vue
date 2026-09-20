<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cehp_jbwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:emoji-edit-20-regular" /></template>
<style>
.cehp_jbwj {
  fill: currentColor;
  d: path("M2 10a8 8 0 0 0 7.009 7.94q.013-.142.05-.287l.173-.695a7.001 7.001 0 1 1 7.698-7.95c.343-.025.69.012 1.022.11A8.001 8.001 0 0 0 2 10m8.274 4.67l.82-.821a4.01 4.01 0 0 1-4.205-1.334a.5.5 0 1 0-.778.629A5 5 0 0 0 9.986 15q.132-.174.288-.33M13.5 8.5a1 1 0 1 0-2 0a1 1 0 0 0 2 0m-5 0a1 1 0 1 0-2 0a1 1 0 0 0 2 0m2.48 6.877l4.83-4.83a1.87 1.87 0 1 1 2.644 2.646l-4.83 4.829a2.2 2.2 0 0 1-1.02.578l-1.498.374a.89.89 0 0 1-1.079-1.078l.375-1.498a2.2 2.2 0 0 1 .578-1.02");
}

</style>
