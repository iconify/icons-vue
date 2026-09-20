<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o7x428_va"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-multiple-20-filled" /></template>
<style>
.o7x428_va {
  fill: currentColor;
  d: path("M16 8.503c.606.456 1 1.18 1 1.997v3a4.5 4.5 0 0 1-4.5 4.5h-4c-.817 0-1.54-.394-1.996-1H12.5a3.5 3.5 0 0 0 3.5-3.5zM9.5 1A3.5 3.5 0 0 1 13 4.5v1.55a2.5 2.5 0 0 1 2 2.45v5a2.5 2.5 0 0 1-2.5 2.5h-6A2.5 2.5 0 0 1 4 13.5v-5a2.5 2.5 0 0 1 2-2.45V4.5A3.5 3.5 0 0 1 9.5 1m0 9a1 1 0 1 0 0 2a1 1 0 0 0 0-2m0-8A2.5 2.5 0 0 0 7 4.5V6h5V4.5A2.5 2.5 0 0 0 9.5 2");
}

</style>
