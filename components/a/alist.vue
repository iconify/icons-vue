<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r10c8vb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alist" /></template>
<style>
.r10c8vb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.33 39.5l8.522-14.762m5.114 8.857L26.557 39.5l15.341-.001L24 8.499l-17.898 31");
}

</style>
