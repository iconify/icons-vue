<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><rect class="ggh4i7b-n"/><path class="c799x4wqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:before-launcher" /></template>
<style>
.c799x4wqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.477 24.666c0-1.05.851-1.902 1.902-1.902h0m-1.902 0v5.04m-11.463-.96c-.327.573-.945.96-1.652.96h0a1.9 1.9 0 0 1-1.902-1.902v-1.236c0-1.05.851-1.902 1.902-1.902h0c1.05 0 1.902.851 1.902 1.902v.618H16.46m21.79 1.56a1.9 1.9 0 0 1-1.652.96h0a1.9 1.9 0 0 1-1.902-1.902v-1.236c0-1.05.852-1.902 1.902-1.902h0c1.05 0 1.902.851 1.902 1.902v.618h-3.804M12.638 24a1.902 1.902 0 1 1 0 3.804H9.5v-7.608h3.138a1.902 1.902 0 1 1 0 3.804m0 0H9.5m13.392 3.804v-6.276c0-.736.596-1.332 1.331-1.332h0c.655 0 1.064.194 1.345.557m-3.804 2.011h2.663");
}

.ggh4i7b-n {
  width: 3.804px;
  height: 5.04px;
  x: 25.696px;
  y: 22.764px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.902px;
  ry: 1.902px;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
