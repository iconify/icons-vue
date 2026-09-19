<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="d p3csvzfke"/><path class="tmp_23j4l"/><path class="b85mdyb9u d"/><circle class="j6qpmlk9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flip-transfer" /></template>
<style>
.b85mdyb9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.428 25.262c-.234 1.957 1.158 3.558 3.094 3.558s3.712-1.601 3.947-3.558l.277-2.313c.235-1.957-1.158-3.558-3.094-3.558s-3.712 1.6-3.947 3.558m.43-3.556l-1.706 14.232m-16.395-4.801l1.407-11.742c.171-1.424 1.355-2.491 2.763-2.491c1.232 0 1.894.356 2.336 1.067m-7.312 3.736h4.929");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.j6qpmlk9d {
  cx: 27.011px;
  cy: 15.125px;
  r: 0.747px;
  fill: currentColor;
}

.p3csvzfke {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.499 19.394l-1.13 9.43");
}

.tmp_23j4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21.779 14.586l-1.493 12.452c-.128 1.068.49 1.78 1.547 1.78h.528");
}

</style>
