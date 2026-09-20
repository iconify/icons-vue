<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dlva9_b6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:gauge-rotate-315-20-filled" /></template>
<style>
.dlva9_b6c {
  fill: currentColor;
  d: path("M10.831 2.043A8.001 8.001 0 0 1 10 18A8 8 0 0 1 4.482 4.207a.75.75 0 0 1 1.036 1.086a6.5 6.5 0 1 0 5.16-1.758a.75.75 0 1 1 .153-1.492m-4.791 4.9c-.392-.558.222-1.232.791-.968l.112.065c1.267.899 2.544 1.784 3.79 2.712c.308.23.576.435.682.541a1.501 1.501 0 0 1-2.122 2.122c-.106-.106-.31-.373-.541-.683A217 217 0 0 1 6.04 6.943");
}

</style>
