<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ln7eusbcc"/><path class="bwwqp8bma"/><path class="qv47gob4h"/><circle class="ern8a8b4l"/><circle class="ssmn0eigx"/><circle class="ply12fb_y"/><circle class="fv9gnxwus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:games-2" /></template>
<style>
.bwwqp8bma {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.044 27.736l4.553 6.83a5.405 5.405 0 0 0 9.786-4.108c-.984-4.67-1.769-9.026-2.572-11.982c-.846-3.113-3.884-5.28-7.284-5.28c-2.052 0-3.912.81-5.288 2.123h-8.478a7.64 7.64 0 0 0-5.287-2.124c-3.401 0-6.44 2.168-7.285 5.28c-.803 2.957-1.588 7.313-2.572 11.983a5.405 5.405 0 0 0 9.787 4.107l4.553-6.83z");
}

.ern8a8b4l {
  cx: 31.03px;
  cy: 20.981px;
  r: 0.75px;
  fill: currentColor;
}

.fv9gnxwus {
  cx: 33.75px;
  cy: 23.695px;
  r: 0.785px;
  fill: currentColor;
}

.ln7eusbcc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.25 23.695v-5.427m-2.713 2.713h5.426m.224-7.289v-1.613c0-.58-.471-1.052-1.052-1.052h-3.77c-.58 0-1.052.471-1.052 1.052v1.77");
}

.ply12fb_y {
  cx: 33.75px;
  cy: 18.268px;
  r: 0.75px;
  fill: currentColor;
}

.qv47gob4h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.813 13.692v-1.613c0-.58.471-1.052 1.052-1.052h3.77c.58 0 1.052.471 1.052 1.052v1.77");
}

.ssmn0eigx {
  cx: 36.463px;
  cy: 20.981px;
  r: 0.75px;
  fill: currentColor;
}

</style>
