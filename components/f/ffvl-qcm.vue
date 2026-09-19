<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e41gw4bcv"/><rect class="nyzssgnyi"/><path class="kc6mf9bss"/><path class="a3_kajboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ffvl-qcm" /></template>
<style>
.a3_kajboh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.997 25.087l.884.884c.18.18.473.18.653 0l4.206-4.206");
}

.e41gw4bcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.498 5.5l4.08 9.328L31.66 5.5h3.227v6.996a2.33 2.33 0 0 0 2.332 2.332h3.497M7.284 10.164h4.547m-4.547 4.664V7.832A2.33 2.33 0 0 1 9.616 5.5h4.663m2.223 4.664h4.547m-4.547 4.664V7.832A2.33 2.33 0 0 1 18.834 5.5h4.664");
}

.kc6mf9bss {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.782 36.871h13.912m-13.912 3.902h9.151m-14.98-19.54h-4.648a1 1 0 0 0-1 .999v5.71a1 1 0 0 0 1 1h5.71a1 1 0 0 0 1-1V25.31m3.767-1.997h13.912m-13.912 3.902h9.151");
}

.nyzssgnyi {
  width: 7.709px;
  height: 7.709px;
  x: 11.306px;
  y: 34.791px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 0.999px;
  ry: 0.999px;
}

</style>
