<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kn-2do22g"/><path class="pv08fxblu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loyalty-app-grocery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kn-2do22g {
  d: path("M10.375 2.5h3.25A4.375 4.375 0 0 1 18 6.875v10.25a4.375 4.375 0 0 1-4.375 4.375h-3.25A4.375 4.375 0 0 1 6 17.125V6.875A4.375 4.375 0 0 1 10.375 2.5m.125 3h3");
}

.pv08fxblu {
  d: path("m12.661 9.84l.313.633a1.5 1.5 0 0 0 1.129.82l.698.102a.737.737 0 0 1 .409 1.257l-.505.493a1.5 1.5 0 0 0-.432 1.328l.119.695a.737.737 0 0 1-1.069.777l-.625-.328a1.5 1.5 0 0 0-1.396 0l-.625.328a.737.737 0 0 1-1.069-.777l.119-.695a1.5 1.5 0 0 0-.432-1.328l-.505-.493a.737.737 0 0 1 .409-1.257l.698-.102a1.5 1.5 0 0 0 1.129-.82l.313-.633a.737.737 0 0 1 1.322 0");
}

</style>
