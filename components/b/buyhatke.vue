<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xgtl3pawe"/><path class="ef534u9yc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:buyhatke" /></template>
<style>
.ef534u9yc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.43 19.228c0-4.868-1.37-13.728-9.162-13.728s-9.16 8.86-9.16 13.728m4.448 2.495h2.715c2.483 0 4.496 2.018 4.496 4.506s-2.013 4.506-4.496 4.506l4.496 4.4m-4.496-13.412h6.173m-8.888 4.528h8.888");
}

.xgtl3pawe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.513 14.359h30.974V42.5H8.513zm0 0l2.908-1.759l-.109-1.759h25.376l-.109 1.759l2.908 1.759");
}

</style>
