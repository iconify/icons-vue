<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="b_6i53biz"/><ellipse class="xdh-w6rae"/><path class="ebq5gdb8n"/><path class="oo5lxgemz"/><path class="az4p02bhx"/><path class="eh3s3mbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flutterhole" /></template>
<style>
.az4p02bhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.31 23.85a10.56 10.56 0 0 1 6.58 4.206m-5.984 2.13a9.95 9.95 0 0 1 4.99 2.636m-15.797-9.28c-.862-2.861-2.874-6.971-4.674-8.809m1.772 12.491c-1.06-2.176-6.002-7.434-9.358-8.279m4.801 8.813c-2.309-1.499-5.42-1.494-6.698-1.496");
}

.b_6i53biz {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 19.5px;
  ry: 10.636px;
}

.ebq5gdb8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.377 29.568a8.417 8.417 0 0 0-16.755 0M24 13.364v8.599m0 12.673v-3.9");
}

.eh3s3mbez {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.69 23.85a10.56 10.56 0 0 0-6.58 4.206m5.984 2.13a9.95 9.95 0 0 0-4.99 2.636");
}

.oo5lxgemz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.9 23.542c.863-2.861 2.875-6.971 4.675-8.809m-1.771 12.491c1.06-2.176 6-7.434 9.358-8.279m-4.802 8.813c2.309-1.499 5.42-1.494 6.699-1.496");
}

.xdh-w6rae {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 14.891px;
  ry: 6.736px;
}

</style>
