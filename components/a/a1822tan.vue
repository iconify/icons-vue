<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uaaz6t0-w"/><circle class="cpk0fnbgt"/><path class="ws_2hgcwx"/><path class="q4jp27afi"/><path class="qw24efqny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:a1822tan" /></template>
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

.q4jp27afi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.34 18.253a2.48 2.48 0 0 0-2.48 2.482h0a2.48 2.48 0 0 0 2.48 2.481h1.614a2.48 2.48 0 0 0 2.481-2.481h0a2.48 2.48 0 0 0-2.481-2.482");
}

.qw24efqny {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.954 18.253a2.48 2.48 0 0 0 2.481-2.481h0a2.48 2.48 0 0 0-2.481-2.482H18.34a2.48 2.48 0 0 0-2.482 2.482h0a2.48 2.48 0 0 0 2.482 2.481m.001 0h1.613");
}

.uaaz6t0-w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.412 27.729v5.865a1.17 1.17 0 0 0 1.095 1.24a1 1 0 0 0 .141 0h.371m-2.844-5.701h2.597m7.876 3.219a2.473 2.473 0 0 1-4.946 0v-1.613a2.473 2.473 0 0 1 4.946 0m0 4.095v-6.576m8.588 6.576v-4.095a2.473 2.473 0 0 0-4.946 0v4.095m0-4.095v-2.481M7.773 23.216h4.946m-4.946-8.561l2.473-1.365m0 0v9.926m14.526-6.7a3.277 3.277 0 1 1 5.564 2.358c-1.36 1.116-5.564 4.342-5.564 4.342h6.553m2.349-6.7a3.277 3.277 0 1 1 5.564 2.358c-1.36 1.116-5.564 4.342-5.564 4.342h6.553");
}

.ws_2hgcwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 7.467;
  d: path("M35.352 29.243v4.946m2.473-2.474h-4.946");
}

</style>
