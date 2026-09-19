<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bq95zz9ig"/><path class="fvwyr9bpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hotdoc" /></template>
<style>
.bq95zz9ig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.906 40.455L24.1 45.5l-6.852-4.981l-8.38-1.245l-1.323-8.368L2.5 24.1l4.982-6.852l1.244-8.38l8.368-1.323L23.9 2.5l6.852 4.982l8.38 1.244l1.323 8.368L45.5 23.9l-4.981 6.852l-1.245 8.38Z");
}

.fvwyr9bpq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.783 19.91v-7.954h8.328v8.141h8.277v7.938h-8.21v8.01H20.01v-8.11h-8.4v-8.033Z");
}

</style>
