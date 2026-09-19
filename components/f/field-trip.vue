<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="fnzjb9y6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:field-trip" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fnzjb9y6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.878 10.996c6.818 1.401 11.555-3.585 21.243-3.646c6.057-.037 11.395 1.768 11.395 1.768M3.22 18.463c3.019-1.925 6.607-3.122 11.864-3.122c7.739 0 21.348 4.605 29.873 3.837M2.51 24.636c8.284-6.477 20.27 1.472 34.023 1.64C41.542 26.337 45.5 24 45.5 24M3.644 30.935c8.468-.3 10.823 3.345 20.749 2.84s14.423-4.106 20.22-3.65M6.682 36.741c8.066-1.227 10.078 5.132 19.561 4.493c9.154-.617 7.64-1.963 13.55-2.646");
}

</style>
