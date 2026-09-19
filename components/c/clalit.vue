<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ntemf6s7j"/><path class="h41fp3byy"/><path class="ioo9a1bif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:clalit" /></template>
<style>
.h41fp3byy {
  d: path("M8.101 21.246h10.653l6.635-5.34s.67-.622 1.292 0l4.773 5.343h9.749L42.5 14.81M5.507 33.184h7.72l6.455 7.55c1.776 1.775 3.657 0 3.657 0l9.205-7.547h6.075l1.28-6.435");
}

.ioo9a1bif {
  d: path("M39.899 26.754H29.246l-6.635 5.34s-.67.622-1.292 0l-4.773-5.343H6.797L5.5 33.19");
}

.ntemf6s7j {
  d: path("M42.493 14.816h-7.72l-6.455-7.55c-1.775-1.775-3.656 0-3.656 0l-9.206 7.547H9.382l-1.28 6.435");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
