<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a2o2o-b7e"/><path class="z-piqbqqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:degoo" /></template>
<style>
.a2o2o-b7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.414 15.19a7.465 7.465 0 0 0-9.148-5.269a7.35 7.35 0 0 0-5.27 9.148c.744 2.333 2.716 3.43 3.927 5.42");
}

.z-piqbqqr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.895 35.687a9.05 9.05 0 0 1-12.8 0a9.19 9.19 0 0 1 0-12.802a9.05 9.05 0 0 1 8.388-2.43a8.95 8.95 0 0 1 5.44 4.034l6.154 9.595a8.95 8.95 0 0 0 5.44 4.033a9.05 9.05 0 0 0 8.387-2.43a9.19 9.19 0 0 0 0-12.801a9.05 9.05 0 0 0-12.8 0");
}

</style>
