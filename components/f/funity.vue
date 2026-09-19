<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hrg67dbdx"/><circle class="rnp_kt62l"/><path class="imacfvdco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:funity" /></template>
<style>
.hrg67dbdx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 12.494h39m-29 0v23m11.174-7.988v8m0-1.699l3.63-3.604m-2.47 2.457l2.84 2.834");
}

.imacfvdco {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18 30.206v5.3m20.72-6.962v5.95a1 1 0 0 0 1 1h.3m-2.35-5.3h2.1m-16.094 4.305c-.345.602-.993 1.007-1.917 1.007s-1.82-.895-1.82-2v-1.3c0-1.104.896-2 1.819-2s1.57.404 1.916 1.004m11.736 3.275a2 2 0 0 1-3.738-.99v-1.3a2 2 0 1 1 4 0v.65h-4");
}

.rnp_kt62l {
  cx: 18px;
  cy: 27.756px;
  r: 0.75px;
  fill: currentColor;
}

</style>
