<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r8cv9cctc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:laudate" /></template>
<style>
.r8cv9cctc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.057 15.656Q43.19 9.847 23.954 4.5l.103 38.702m-5.255.298h10.396M11.79 39.305l24.348-21.387m-23.844 0l23.844 21.387M13.046 29.54H9.368m-.911 1.821l2.75-5.499l2.75 5.499m20.086 0h1.836v-.155a2.751 2.751 0 1 1 1.828 0v.156h1.836");
}

</style>
