<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ioecq2crg"/><path class="jh1zi08uc"/><path class="xqkv3acbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:carpay" /></template>
<style>
.ioecq2crg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.945 8.797A21.5 21.5 0 0 1 27.148 2.5m15.203 6.297l-7.071 7.071c-4.491-4.491-11.772-4.491-16.263 0s-4.491 11.772 0 16.263s11.772 4.491 16.263 0l3.535 3.536a16.5 16.5 0 0 1-11.667 4.832");
}

.jh1zi08uc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.481 35.667A16.5 16.5 0 0 1 27.148 7.499");
}

.xqkv3acbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.351 39.203A21.5 21.5 0 0 1 5.649 24");
}

</style>
