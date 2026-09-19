<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="p3tc1xk7n"/><path class="rqie2m1iq"/><path class="xv17dwbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kagi-small-web" /></template>
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

.p3tc1xk7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.572 25.645c.49-.054 1.006-.068 1.51-.068C15.08 25.577 24 34.497 24 45.496M24 2.5v11.436");
}

.rqie2m1iq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.447 26.617C9.845 14.556 15.677 8.218 24 4.254m-7.133 25.969c.24-7.367.811-11.846 7.133-16.287m21.428 11.709a14 14 0 0 0-1.51-.068C32.92 25.577 24 34.497 24 45.496");
}

.xv17dwbei {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.553 26.617C38.155 14.556 32.323 8.218 24 4.254m7.133 25.969c-.24-7.367-.811-11.846-7.133-16.287");
}

</style>
