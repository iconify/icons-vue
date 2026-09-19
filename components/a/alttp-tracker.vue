<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="xcanw6b2x"/><path class="ear46ltwd"/><path class="k95fkeb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:alttp-tracker" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ear46ltwd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.771 33.61v-1.416h-3.245V30.91h-1.504v-1.823H12.5l.016-10.174h1.522v-1.82h1.504v-1.287h3.245V14.39h10.426v1.416h3.245v1.287h1.504v1.82h1.522l.016 10.174h-1.522v1.823h-1.504v1.284h-3.245v1.416z");
}

.k95fkeb0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.149 22.679h1.831v.953h1.21v.888h3.523v-.888h1.228v-.953h1.9v-3.455H27.01v-1.326h-1.468v-.889h-2.986v.889h-1.507v1.326h-1.9z");
}

.xcanw6b2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.694 20.974h2.699m8.044 2.487v2.368h-.805v.803H29.32v1.446H18.766v-1.446h-3.205v-.803h-.837v-2.368");
}

</style>
