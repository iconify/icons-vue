<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="jxg7jjbid"/><rect class="o7dpzubxp"/><path class="y0o2lhbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aevo-ihk" /></template>
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

.jxg7jjbid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.213 19.963l-2.712 8.189l-2.713-8.189m-6.352 4.095h2.669m1.425 4.094h-4.094v-8.189h4.094");
}

.o7dpzubxp {
  width: 5.425px;
  height: 8.189px;
  x: 31.854px;
  y: 19.963px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.713px;
  ry: 2.713px;
}

.y0o2lhbtr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.248 25.439H11.62m-.899 2.713l2.713-8.189l2.712 8.189m.656 2.506v8.189m2.568-8.189v8.189m5.426-8.189v8.189m-5.426-4.11h5.426m2.568-4.079v8.189m0-2.853l4.401-5.309m0 8.162l-3.371-4.095");
}

</style>
