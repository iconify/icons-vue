<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cts1h-bqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-line-32-filled" /></template>
<style>
.cts1h-bqk {
  fill: currentColor;
  d: path("M21 9a4 4 0 1 1 3.08 3.894l-2.372 3.162a4 4 0 1 1-6.066 5.118l-4.651 1.55Q11 22.86 11 23a4 4 0 1 1-.642-2.174l4.651-1.55a4 4 0 0 1 4.91-4.17l2.373-3.162A4 4 0 0 1 21 9");
}

</style>
