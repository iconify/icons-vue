<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="lsc_6ibui"/><path class="lvz2ylb3f"/><circle class="cpk0fnbgt"/><path class="b96hd7b1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fuelio" /></template>
<style>
.b96hd7b1o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 21.581l-4.22-12.08M24 5.885v2.688m12.79 2.61l-1.9 1.9m-23.68-1.9l1.9 1.9");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.lsc_6ibui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.503 41.117V27.38a2.296 2.296 0 0 0-2.295-2.295h-4.59a2.297 2.297 0 0 0-2.294 2.295v13.738Zm-2.2-13.595h-4.779v4.206h4.779Zm2.2 6.023a1.73 1.73 0 0 1 1.965 1.77l.157 3.567a1.466 1.466 0 0 0 1.55 1.496a1.53 1.53 0 0 0 1.44-1.496c-.008-2.283 0-6.323 0-9.095l-3.376-3.61");
}

.lvz2ylb3f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.615 30.157a1.274 1.274 0 1 1-.864-1.21M3.71 16.878c13.898 6.247 27.427 6.295 40.58 0");
}

</style>
