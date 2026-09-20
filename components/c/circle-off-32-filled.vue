<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="izxvme-db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-off-32-filled" /></template>
<style>
.izxvme-db {
  fill: currentColor;
  d: path("M2.293 2.293a1 1 0 0 1 1.414 0l26 26a1 1 0 1 1-1.414 1.414l-3.127-3.127A13.94 13.94 0 0 1 16 30C8.268 30 2 23.732 2 16c0-3.506 1.288-6.712 3.418-9.168L2.293 3.707a1 1 0 0 1 0-1.414M16 2c7.732 0 14 6.268 14 14c0 2.962-.921 5.71-2.491 7.972L8.027 4.492A13.94 13.94 0 0 1 16 2");
}

</style>
