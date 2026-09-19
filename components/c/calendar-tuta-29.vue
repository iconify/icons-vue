<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="oiio5db6v"/><path class="ugzdnya4i"/></g><path class="bag4m3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-tuta-29" /></template>
<style>
.bag4m3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

.oiio5db6v {
  d: path("M13.544 25.6c.815-2.667 3.6-4.8 6.09-4.8s4.147 2.133 3.332 4.8c-.38 1.244-1.294 2.489-2.455 3.378c-2.445 1.6-9.902 6.222-9.902 6.222h9.422M31.67 20.8c2.65 0 4.142 2.149 3.332 4.8s-3.616 4.8-6.267 4.8s-4.143-2.149-3.333-4.8s3.617-4.8 6.268-4.8");
}

.ugzdnya4i {
  d: path("M23.544 33.422c.385 1.067 1.412 1.778 3.368 1.778h.355c2.667 0 5.452-2.133 6.268-4.8l1.467-4.8");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
