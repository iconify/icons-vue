<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o0rlizpyz"/><path class="gzeag81wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-arts-and-culture-alt" /></template>
<style>
.gzeag81wd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.85 17.781c-6.998 0-12.674 5.676-12.674 12.675c0 7.01 5.676 12.675 12.675 12.675c2.535 0 4.905-.75 6.888-2.04m10.085-8.422H35.67a12.3 12.3 0 0 1-1.544 3.065m3.237 7.766L18.11 25.267");
}

.o0rlizpyz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.354 24.916c5.638 0 10.208-4.57 10.208-10.208S28.992 4.5 23.354 4.5S13.146 9.07 13.146 14.708");
}

</style>
