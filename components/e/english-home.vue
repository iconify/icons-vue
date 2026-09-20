<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="rmdib26_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:english-home" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.rmdib26_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.029 18.277v4.601h2.301m2.357-4.601v4.601m-15.529 0v-4.601l3.049 4.601v-4.601m20.245 0v4.601m3.048-4.601v4.601m-3.048-2.358H39.5m-8.397 1.84c.288.346.633.518 1.15.518h.69c.633 0 1.151-.517 1.151-1.15s-.518-1.15-1.15-1.15h-.748c-.633 0-1.15-.518-1.15-1.15c0-.633.517-1.15 1.15-1.15h.69c.518 0 .863.114 1.15.517M8.5 20.578h1.495m.806 2.3H8.5v-4.601h2.301m10.869 1.496c0-.863-.69-1.553-1.553-1.553c-.862 0-1.553.69-1.553 1.553v1.553c0 .862.69 1.495 1.553 1.495s1.553-.69 1.553-1.495h-1.553m-6.096 3.853v4.601m3.048-4.601v4.601m-3.048-2.358h3.048m14.774.058h1.496m.805 2.3h-2.301v-4.601h2.301M20.885 29.78zc-.863 0-1.496-.69-1.496-1.495v-1.553c0-.863.69-1.553 1.496-1.553c.862 0 1.553.69 1.553 1.553v1.495c0 .863-.69 1.553-1.553 1.553m3.872-.057v-4.544l2.301 4.601l2.3-4.601v4.601");
}

</style>
