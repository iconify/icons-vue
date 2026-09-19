<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dum-znb6x"/><path class="a8l8hmbvm"/><circle class="l7-cw87ac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:banco-azteca" /></template>
<style>
.a8l8hmbvm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.975 12.703c7.55 1.594 16.035 4.767 19.91 11.042c3.522 5.703 1.16 10.534-4.26 11.433c8.492.725 12.07-1.901 11.868-7.216c-.19-5.001-6.92-9.737-11.868-12.085c-4.743-2.251-11.143-2.797-15.65-3.174");
}

.dum-znb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.025 12.703c-7.55 1.594-16.035 4.767-19.91 11.042c-3.522 5.703-1.16 10.534 4.26 11.433c-8.491.725-12.07-1.901-11.868-7.216c.19-5.001 6.92-9.737 11.868-12.085c4.743-2.251 11.143-2.797 15.65-3.174");
}

.l7-cw87ac {
  cx: 24.047px;
  cy: 27.115px;
  r: 6.422px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
