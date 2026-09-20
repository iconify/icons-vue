<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mem18ybbx"/><path class="pehpvuz3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:amazon-aws-console" /></template>
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

.mem18ybbx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.28 29.7c1.113-.45 3.092-1.048 3.688-.326c.644.781-.17 2.477-.92 3.794");
}

.pehpvuz3c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.798 30.223c1.759 1.397 6.954 3.535 12.488 3.535c3.63.086 7.194-.993 10.167-3.08m-5.926-11.93l-2.025 6.504l-2.024-6.504l-2.025 6.504l-2.024-6.504m9.985 5.955c.448.376.931.549 2.018.549h.55c.896 0 1.622-.728 1.622-1.626S33.879 22 32.983 22h-1.1a1.624 1.624 0 0 1-1.623-1.626c0-.898.726-1.626 1.622-1.626h.55c1.087 0 1.57.173 2.019.55m-16.148 3.5a2.454 2.454 0 0 1-4.908 0v-1.596a2.454 2.454 0 0 1 4.908 0m0 4.05v-6.504");
}

</style>
