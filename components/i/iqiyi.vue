<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="j3qdlsbya"/><path class="rm97m4b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:iqiyi" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.j3qdlsbya {
  fill: currentColor;
  d: path("M11.836 19.016c0 .414-.333.75-.744.75a.747.747 0 0 1-.744-.75c0-.414.333-.75.744-.75c.41 0 .744.336.744.75");
}

.rm97m4b7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.092 22.216v7.199m10.197 0l-3.438-3.6m-.001 3.6c-1.983 0-3.437-1.6-3.437-3.466v-3.6c0-2 1.586-3.6 3.438-3.6h0c1.983 0 3.438 1.6 3.438 3.6v3.466c0 2-1.455 3.6-3.438 3.6m6.494-10.665v10.665m9.933-10.665l-3.438 5.332l-3.438-5.332m3.438 10.665v-5.333m6.494-5.332v10.665");
}

</style>
