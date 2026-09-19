<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mkx-tvc0j"/><path class="hpyk3k9df"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bmap" /></template>
<style>
.hpyk3k9df {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.89 34.13c-3.6.9-6 2.48-6 4.27c0 2.82 5.85 5.1 13.08 5.1s13.08-2.28 13.08-5.1c0-1.77-2.31-3.33-5.83-4.24");
}

.mkx-tvc0j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5A11.5 11.5 0 0 0 12.5 16c0 9 8.78 19.83 11.08 22.49a.71.71 0 0 0 1 .07l.07-.07C26.92 35.82 35.5 25 35.5 16A11.5 11.5 0 0 0 24 4.5m0 14.62a3.9 3.9 0 1 1 3.9-3.89a3.9 3.9 0 0 1-3.9 3.89");
}

</style>
