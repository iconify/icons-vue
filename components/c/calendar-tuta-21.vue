<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mmpagmb1h"/><path class="bag4m3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-tuta-21" /></template>
<style>
.bag4m3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

.mmpagmb1h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.193 25.6c.815-2.667 3.6-4.8 6.09-4.8s4.147 2.133 3.332 4.8c-.38 1.244-1.294 2.489-2.455 3.378c-2.445 1.6-9.902 6.222-9.902 6.222h9.422m7.907-12.42l4.205-1.98m0 0L29.39 35.2");
}

</style>
