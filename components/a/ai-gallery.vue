<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xh-98u1bx"/><path class="cxyq8xy4n"/><circle class="x0m1mj5dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ai-gallery" /></template>
<style>
.cxyq8xy4n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.042 30.514l6.585-8.828L43.5 39.446l-16.157.065M16.582 21.817l-4.186 9.321l8.7.066ZM8.864 39.54l1.406-3.855h12.494l2.028 3.83m6.835-17.829v17.808M35 26.731V39.48");
}

.x0m1mj5dq {
  cx: 32.151px;
  cy: 12.561px;
  r: 4.105px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xh-98u1bx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.25 18.088l9.976 18.25c.956 1.75 1.113 3.17-.883 3.173l-20.965.033c-1.35.002-2.43-.876-1.57-2.453l10.368-19.003c1.146-2.101 2.56-.94 3.074 0");
}

</style>
