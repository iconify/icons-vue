<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qpxmxl9gw"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gall-and-gall" /></template>
<style>
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

.qpxmxl9gw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.552 21.949a4.026 4.026 0 0 0-8.052 0v4.102a4.026 4.026 0 0 0 8.052 0h-4.026M37.5 21.949a4.026 4.026 0 0 0-8.052 0v4.102a4.026 4.026 0 0 0 8.052 0h-4.026m-6.051 4.026h-.69a1.43 1.43 0 0 1-1.157-.589l-2.834-3.896c-.365-.478-1.005-1.108-1.005-2.04c0-.881.715-1.647 1.71-1.647c.969 0 1.656.766 1.656 1.646c0 .933-.756 1.73-2.152 1.995c-1.557.296-2.53 1.15-2.53 2.558c0 1.139.717 1.973 2.152 1.973c1.886 0 2.996-1.788 4.636-3.986");
}

</style>
