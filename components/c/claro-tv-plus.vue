<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uo47pyvli"/><path class="kfa82dbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:claro-tv-plus" /></template>
<style>
.kfa82dbcu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.733 24.049a2.1 2.1 0 0 1 2.101 2.101v1.366a2.1 2.1 0 0 1-2.1 2.101h0a2.1 2.1 0 0 1-2.102-2.101V26.15a2.1 2.1 0 0 1 2.101-2.101m-5.591 2.101a2.1 2.1 0 0 1 2.101-2.101m-2.101 0v5.568m-8.097-8.405v8.405m6.107-2.101a2.101 2.101 0 1 1-4.202 0V26.15a2.101 2.101 0 1 1 4.202 0m0 3.467v-5.568m-8.084 2.749v.034a2.784 2.784 0 0 1-5.568 0v-2.836a2.784 2.784 0 0 1 5.568 0v.034m15.665-2.083v-3.564m3.168 4.941l3.152-3.152m-2.117 6.661H38.5m-6.032 7.226l-2 5.3l-2-5.3m-2.951-1.65v5.95a1 1 0 0 0 1 1h.3m-2.35-5.3h2.1m7.551 2.65h4m-2-2v4");
}

.uo47pyvli {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 42.5h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4");
}

</style>
