<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v1jjv7art"/><ellipse class="evoqi2rze"/><path class="dj7e-hb6k"/><ellipse class="fkr479bnn"/><path class="xsg4ifbsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:9292" /></template>
<style>
.dj7e-hb6k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.609 18.53c.574.723 1.449 1.22 2.9 1.22h.241c1.903 0 3.446-1.483 3.446-3.312v-3.375m11.742 0a3.313 3.313 0 0 1 6.625 0c0 .914-.334 1.783-.97 2.342c-1.34 1.176-5.656 4.345-5.656 4.345h6.625M11.438 31.563a3.313 3.313 0 0 1 6.624 0c0 .914-.333 1.783-.97 2.342c-1.34 1.176-5.654 4.345-5.654 4.345h6.625");
}

.evoqi2rze {
  cx: 14.75px;
  cy: 13.063px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.446px;
  ry: 3.313px;
}

.fkr479bnn {
  cx: 33.25px;
  cy: 31.563px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.446px;
  ry: 3.313px;
}

.v1jjv7art {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 42.5h-29c-2.2 0-4-1.8-4-4v-29c0-2.2 1.8-4 4-4h29c2.2 0 4 1.8 4 4v29c0 2.2-1.8 4-4 4M24 5.5v37M5.5 24h37");
}

.xsg4ifbsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.109 37.03c.574.723 1.449 1.22 2.9 1.22h.241c1.903 0 3.446-1.483 3.446-3.312v-3.376");
}

</style>
