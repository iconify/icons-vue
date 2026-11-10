<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="h1dejhbun"/><path class="rpgmxwb-e"/><path class="m0f-c6bsy"/><path class="gqes7zb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:gakumasu" /></template>
<style>
.gqes7zb3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 36.576c10.514-5.06 23.747-8.14 32-7.785");
}

.h1dejhbun {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.902 15.55c-.726 2.981-.99 6.242-.939 9.688");
}

.m0f-c6bsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.453 7.096c.777 1.567 2.14 3.831 3.35 5.224m1.67-6.798c.22 1.895.783 3.627 1.775 5.53m7.156-7.576c-2.006 2.884-3.594 5.141-5.018 7.06M18.673 20.87c3.795-4.834 14.386-7.263 2.777 5.166c2.012-1.793 4.616.104 4.806 2.8c.429 6.08-1.27 10.667-2.166 13.274c-1.132 3.29-1.907 2.92-4.853.667");
}

.rpgmxwb-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.582 18.093c10.255-8.038 32.362-12.082 30.28-6.832c-1.138 2.871-2.843 5.58-5.631 8.71");
}

</style>
