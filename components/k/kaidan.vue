<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p-3zw4jzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kaidan" /></template>
<style>
.p-3zw4jzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5A21.471 21.471 0 0 0 6.693 36.718a21.4 21.4 0 0 0-3.818 6.332a.995.995 0 0 0 .728 1.343C5.606 44.806 9.113 45.5 24 45.5a21.5 21.5 0 0 0 0-43m-9.5 12.851h19m-11 17.299h11m-19 0h4m-8-8.65h27");
}

</style>
