<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8wl3yb5t"/><circle class="u3ndg0b-t"/><path class="opwbvfsxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:axio" /></template>
<style>
.o8wl3yb5t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.293 23.962l-17.15 17.15c-1.716 1.716-4.54 1.716-6.256 0h0c-1.715-1.714-1.715-4.54 0-6.254l10.896-10.896L6.786 13.067c-1.715-1.716-1.715-4.54 0-6.255h0c1.715-1.716 4.54-1.716 6.255 0z");
}

.opwbvfsxu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.872 34.152l6.254-6.255l7.062 7.062c1.715 1.715 1.715 4.54 0 6.255h0c-1.715 1.715-4.54 1.715-6.255 0z");
}

.u3ndg0b-t {
  cx: 36.85px;
  cy: 11.15px;
  r: 5.65px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
