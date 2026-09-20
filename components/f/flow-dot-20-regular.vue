<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xphsg_xdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flow-dot-20-regular" /></template>
<style>
.xphsg_xdy {
  fill: currentColor;
  d: path("M5 2.5A2 2 0 0 1 6.935 4H14a3 3 0 1 1 0 6H6a2 2 0 1 0 0 4h7.065A1.999 1.999 0 1 1 15 16.5a2 2 0 0 1-1.935-1.5H6a3 3 0 1 1 0-6h8a2 2 0 1 0 0-4H6.935A1.999 1.999 0 0 1 3 4.5a2 2 0 0 1 2-2");
}

</style>
