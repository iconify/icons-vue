<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h7kuf_bxl"/><path class="b3wvv-gmt"/><path class="ktf6mc6jz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dina" /></template>
<style>
.b3wvv-gmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.192 17.772c4.697.92 8.27 2.961 10.618 6.126c-2.348 3.165-5.82 5.207-10.618 6.126q1.685-6.126 0-12.252");
}

.h7kuf_bxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.085 43.296V4.5h8.78c9.189 0 17.05 7.76 17.05 17.05v4.9c0 9.189-7.76 17.05-17.05 17.05h-8.78zm0-19.398h10.84");
}

.ktf6mc6jz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.192 17.772c.817-2.246.817-4.288 0-6.33c7.045 1.532 9.495 6.432 10.618 12.456c-1.02 6.024-3.471 10.924-10.618 12.456c.817-2.042.817-4.084 0-6.33");
}

</style>
