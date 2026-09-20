<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sad2_kazc"/><path class="bag4m3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-tuta-25" /></template>
<style>
.bag4m3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

.sad2_kazc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.643 25.6c.815-2.667 3.6-4.8 6.09-4.8s4.148 2.133 3.332 4.8c-.38 1.244-1.294 2.489-2.455 3.378c-2.444 1.6-9.902 6.222-9.902 6.222h9.422m4.128-1.215c.739.833 1.587 1.215 3.997 1.215h.414c2.23 0 4.59-1.807 5.271-4.037c.682-2.23-.573-4.037-2.802-4.037h-4.783l1.934-6.326h8.82");
}

</style>
