<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ee_wstb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:layout-column-two-edit-20-filled" /></template>
<style>
.ee_wstb8j {
  fill: currentColor;
  d: path("M15.81 10.548a1.87 1.87 0 1 1 2.644 2.644l-4.829 4.83a2.2 2.2 0 0 1-1.021.578l-1.498.375a.89.89 0 0 1-1.079-1.08l.374-1.497c.097-.387.297-.74.579-1.021zM9.5 15.925a3 3 0 0 0-.067.23L9.222 17H6a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h3.5zM14 3a3 3 0 0 1 3 3v3.006c-.69.032-1.37.308-1.898.835L10.5 14.443V3z");
}

</style>
