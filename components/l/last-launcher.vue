<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="mpnl0bbeb"/><path class="lvtit0b2e"/><path class="budceum8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:last-launcher" /></template>
<style>
.budceum8y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.719 18.006c.299 5.957-.698 10.02-2.692 13.709");
}

.lvtit0b2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.853 36.75l.437-1.695l4.199 2.99l3.39-10.767l-2.244-2.094C33.482 15.164 31.538 8.784 24 3.5c-7.538 5.284-9.482 11.665-8.635 21.684l-2.243 2.094l3.39 10.767l4.198-2.99l.438 1.694zm-.415 2.169L24 44.5l-2.438-5.581z");
}

.mpnl0bbeb {
  cx: 24px;
  cy: 15.713px;
  r: 3.29px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
