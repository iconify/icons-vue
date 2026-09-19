<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="xftu0-hel"/><path class="cgj4q0bqv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:klook" /></template>
<style>
.cgj4q0bqv {
  d: path("M17.073 18.819v8.077c0 .692.469 1.154 1.171 1.154h.352m1.489-3.808c0-1.27 1.054-2.308 2.343-2.308s2.342 1.039 2.342 2.308v1.5c0 1.27-1.054 2.308-2.342 2.308s-2.343-1.038-2.343-2.308zm13.475-5.539v9.347m0-1.962l4.217-4.27m-2.811 2.886l3.28 3.23M26.82 24.242c0-1.27 1.055-2.308 2.343-2.308s2.343 1.039 2.343 2.308v1.5c0 1.27-1.054 2.308-2.343 2.308s-2.342-1.038-2.342-2.308z");
}

.xftu0-hel {
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4m.89 13.203v9.347m0-1.962l4.217-4.27m-2.812 2.886l3.28 3.23");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
