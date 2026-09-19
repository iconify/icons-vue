<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="dgfgc_bdd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:baidu-homework" /></template>
<style>
.dgfgc_bdd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.417 31.481L34.536 28.4M25.88 17.569c-2.303-2.036-4.56-.465-6.555 2.468c-1.57 2.309-1.666 4.953.08 5.738c3.124 1.404 7.413-6.04 6.123-7.853M36 17.44c-2.304-2.036-4.561-.465-6.556 2.467c-1.57 2.31-1.667 4.953.08 5.738c3.123 1.404 7.412-6.04 6.123-7.853m-21.851.21c1.57-.866 2.468-1.042 2.468-1.042l-4.263 10.081");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
