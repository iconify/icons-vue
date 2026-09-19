<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h9e-wc98o"/><path class="ebb2v4s4b"/><path class="syofc7aal"/><path class="ix49xbc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:grokio" /></template>
<style>
.ebb2v4s4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.849 35.598a15.35 15.35 0 0 0 5.085-11.682a15.15 15.15 0 0 0-5.07-11.5a3.936 3.936 0 0 1 5.144-5.96a23 23 0 0 1 7.798 17.44a24.5 24.5 0 0 1-.447 4.735");
}

.h9e-wc98o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.598 41.151a15.35 15.35 0 0 0-11.636-5.085h-.046a15.15 15.15 0 0 0-11.5 5.07a3.936 3.936 0 0 1-5.96-5.144a23 23 0 0 1 17.44-7.798h.066a24.5 24.5 0 0 1 4.67.447");
}

.ix49xbc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.151 12.402a15.35 15.35 0 0 0-5.085 11.682a15.15 15.15 0 0 0 5.07 11.5a3.936 3.936 0 1 1-5.144 5.96a23 23 0 0 1-7.798-17.44a24.5 24.5 0 0 1 .447-4.736");
}

.syofc7aal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.402 6.849a15.35 15.35 0 0 0 11.636 5.085h.046a15.15 15.15 0 0 0 11.5-5.07a3.936 3.936 0 0 1 5.96 5.144a23 23 0 0 1-17.44 7.798h-.066a24.5 24.5 0 0 1-4.67-.447");
}

</style>
