<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="mlz1lzbof"/><path class="wl8pfn4lc"/><ellipse class="rblfjzfrd"/><path class="d1teqcbme"/><path class="oqef2uzmq"/><ellipse class="jd1i67ugo"/><path class="r3ccetbql"/><path class="gr5mgdafd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:balarama" /></template>
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

.d1teqcbme {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.56 25.236c-.07-1.077-.141-2.153.212-3.035s1.13-1.57 1.85-1.625c.719-.055 1.38.524 1.712.89c.33.365.33.517.33 1.495v4.59");
}

.gr5mgdafd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.302 23.573c.698-.515 1.396-1.03 1.978-.93c.58.098 1.045.81.836 1.726c-.21.915-1.09 2.034-1.973 3.153");
}

.jd1i67ugo {
  cx: 33.254px;
  cy: 25.113px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.471px;
  ry: 2.384px;
}

.mlz1lzbof {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.407 27.557h-5.342v-4.511c0-.97 0-1.14.267-1.453s.799-.771 1.32-.792c.522-.02 1.032.398 1.292.675c.26.278.27.416.28.554");
}

.oqef2uzmq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.635 21.883c.688-.623 1.377-1.247 2.069-1.279c.691-.032 1.387.527 1.685 1.489c.298.961.198 2.325-.31 3.301s-1.42 1.565-1.655 1.86s.208.299.652.301l3.524-.014m0-.001v-6.968");
}

.r3ccetbql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.724 25.113c-.043-1.145-.085-2.29-.473-3.165s-1.121-1.48-1.956-1.443c-.834.038-1.769.72-2.12 2c-.353 1.282-.122 3.163.108 5.044m6.019-.034v-3.538c0-.8 0-1.029.106-1.534s.317-1.287 1.089-1.677s2.104-.39 2.865-.037s.95 1.062 1.046 1.494c.095.432.095.588.095 1.43v3.904m-5.201-.042l5.2.041");
}

.rblfjzfrd {
  cx: 7.742px;
  cy: 25.235px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.181px;
  ry: 2.272px;
}

.wl8pfn4lc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.228 22.03v3.596H23.07m5.337 1.931v-6.999m-10.163 2.82c0-.708 0-1.417.229-1.94c.228-.523.685-.861 1.227-.88a1.63 1.63 0 0 1 1.485.92c.315.636.317 1.606.293 2.537s-.074 1.824-.343 2.471c-.27.648-.757 1.052-1.286 1.062c-.53.01-1.101-.375-1.387-.921c-.286-.547-.286-1.255-.286-1.963");
}

</style>
