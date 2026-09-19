<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cqxe9frdt"/><path class="bag4m3bbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-tuta-3" /></template>
<style>
.bag4m3bbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.27h28.377L42.5 13.893H14.123zm37-28.428H14.123L5.5 5.73h28.377zM5.5 42.27V5.73");
}

.cqxe9frdt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.845 33.985c.74.833 1.696 1.215 4.107 1.215h.561c1.988 0 4.092-1.611 4.7-3.6h0c.607-1.987-.511-3.598-2.5-3.598m-3.206-5.999c1.25-.83 2.44-1.21 4.849-1.203l.559.003c1.987 0 3.106 1.612 2.498 3.6h0c-.607 1.987-2.711 3.599-4.7 3.599m-2.766 0h2.767");
}

</style>
