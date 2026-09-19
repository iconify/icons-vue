<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hkc22ac1t"/><circle class="n8u-5918s"/><path class="dhlck2b_k"/><path class="zdt81t3_h"/><path class="io1s09boz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lecturio-nursing" /></template>
<style>
.dhlck2b_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m18.722 18.52l11.07 5.51l-8.78 5.506z");
}

.hkc22ac1t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.517 40.564v-6.55l4.339 6.55v-6.55");
}

.io1s09boz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.068 36.809c-3.286.338-6.78-.459-9.476-2.194c1.889 2.707 5.623 4.104 9.585 4.093m9.193-8.875c.447-1.277.687-2.751.687-4.41c0-11.288-15.109-17.456-19.88-14.542c6.168-5.185 24.356.94 24.356 14.542c.033 2.5-.524 4.628-1.507 6.408");
}

.n8u-5918s {
  cx: 35.687px;
  cy: 37.289px;
  r: 7.642px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zdt81t3_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.23 42.638C19.739 44.298 3.112 39.2 3.33 21.7C3.33-.341 29.914 3.6 34.259 9.593C29.476 6.678 8.199 2.301 8.199 21.7c0 13.897 11.594 19.05 20.742 19.192");
}

</style>
