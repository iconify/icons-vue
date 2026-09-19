<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="p3shpjq2z"/><path class="bn2wly1af"/></g><path class="oi9e4ebyl"/><path class="bkc65hk2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fonts" /></template>
<style>
.bkc65hk2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.923 12.796h5.337l7.422 22.408h-5.337m11.961-7.423v7.423");
}

.bn2wly1af {
  d: path("M33.101 20.359h5.497c2.958 0 4.902 1.3 4.902 4.818v10.027h-5.497V25.177c0-3.517-1.944-4.818-4.902-4.818c-2.605 0-3.552.118-4.902 1.47");
}

.oi9e4ebyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.886 27.781H6.959M4.5 35.204l7.423-22.408l7.422 22.408");
}

.p3shpjq2z {
  d: path("M30.482 27.781h7.521m-7.521 0c-2.034 0-3.683 1.662-3.683 3.712s1.649 3.711 3.683 3.711h1.951c3.07 0 5.56-2.508 5.56-5.602");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
