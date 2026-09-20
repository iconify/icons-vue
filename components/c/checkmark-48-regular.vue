<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vxkwxhj6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:checkmark-48-regular" /></template>
<style>
.vxkwxhj6j {
  fill: currentColor;
  d: path("M40.139 12.871a1.25 1.25 0 0 1-.01 1.768l-22.25 22a1.25 1.25 0 0 1-1.75.007l-9.25-9a1.25 1.25 0 1 1 1.743-1.792L16.993 34l21.378-21.138a1.25 1.25 0 0 1 1.768.01");
}

</style>
