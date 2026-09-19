<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="w5yrfppmi"/><path class="ugi2uu14x"/><path class="efe65ysvx"/><path class="xkff8qqpf"/><path class="s6puqib0w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fitcloudpro" /></template>
<style>
.efe65ysvx {
  d: path("M5.485 21.792c6.623-1.77 16.15-4.595 16.818-7.37c.59-2.454-1.026-4.045-6.013-5.882c-2.14-.789-3.74-1.899-2.707-3.047");
}

.s6puqib0w {
  d: path("M15.546 5.492c-1.3 1.396 1.947 2.39 6.229 4.061c5.701 2.227 7.57 6.125 1.473 9.372c-5.44 2.897-11.286 5.39-17.731 7.534");
}

.ugi2uu14x {
  d: path("M11.511 42.509c9.316-4.905 23.136-15.378 27.4-21.657c3.925-5.778-5.12-9.87-10.703-11.57c-3.5-1.064-9.739-2.425-9.555-3.79");
}

.w5yrfppmi {
  d: path("M9.515 5.492h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.xkff8qqpf {
  d: path("M17.093 5.493c-.61 1.327 2.625 2.21 7.156 3.603c8.745 2.69 11.452 7.05 5.947 11.214c-6.772 5.123-15.667 10.108-24.68 14.294");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
