<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s8j5-hb0h"/><path class="j_0o6zb_t"/><circle class="y7hiu3bto"/><path class="tdaj4dbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:find" /></template>
<style>
.j_0o6zb_t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.583 42.5l-4.823-7.2c-3.51-5.241.758-14.449 8.863-14.393S42.5 27.27 42.5 27.27");
}

.s8j5-hb0h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4m4 29.597L37.85 42.5");
}

.tdaj4dbfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.76 35.3c-4.137 2.112-7.396 4.704-10.832 7.2");
}

.y7hiu3bto {
  cx: 32.881px;
  cy: 31.023px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
