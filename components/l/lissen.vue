<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v57sjwhxm"/><path class="eoitglb1n"/><path class="t0uthsbhs"/><ellipse class="unvmlabtw"/><ellipse class="utw9e9b7x"/><path class="d24rkz_im"/><path class="fz5w84f5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lissen" /></template>
<style>
.d24rkz_im {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.512 11.139l-.056-5.375c-.004-.432.277-.704.682-.704h1.491c.647-.035.69.354.788.704l.008 5.368m-8.592-1.183l.02-4.27c.01-1.893 1.358-1.064 2.046-.534L23.007 6");
}

.eoitglb1n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.228 21.456c9.745-3.58 14.445 2.55 14.72 5.017c1.062 9.553-7.233 3.865-3.102 16.884");
}

.fz5w84f5w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.07 8.647q-1.228.05-3.238 1.302m5.624-4.185l-.554-.619c-.89-.996-1.947-.67-1.895.854l.17 5.039");
}

.t0uthsbhs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.056 19.898c1.62.417 1.948 1.45 0 2.476m6.604-4.547c.842 1.106 1.902.8 2.45-.128");
}

.unvmlabtw {
  cx: 26.98px;
  cy: 16.044px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.11px;
  ry: 5.121px;
}

.utw9e9b7x {
  cx: 26.948px;
  cy: 16.204px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.555px;
  ry: 2.561px;
}

.v57sjwhxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.833 9.949c-5.008 3.951-2.81 5.682-8.777 9.949c-.822.298-.753 1.464 0 2.476c.808 1.087 2.39 3.013 6.476 2.904c2.905-.078 3.403 2.662 2.641 4.419q-2.787 7.074-1.129 13.044c6.568.958 13.142 1.946 18.49-3.373V21.734c-.14-3.572-3.206-11.632-9.074-13.344");
}

</style>
