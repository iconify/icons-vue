<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jr-kjlewa"/><path class="il7hh6whz"/><path class="lcbd-ac6c"/><path class="xyn1i7rxo"/><path class="gq0_1_m5f"/><path class="h56oyqbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japan-post-bank-fido" /></template>
<style>
.gq0_1_m5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.085 26.211c2.222 2.14 7.252 1.326 8.286 0m-17.483-1.324c0 5.254-3.593 12.028-5.429 12.835");
}

.h56oyqbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.493 31.709c1.56 2.737 5.098 6.24 6.35 6.503m-2.868-7.449c1.119 1.89 3.45 4.243 4.105 4.545m-8.064 3.43s.584-.322.918-1.045a4.3 4.3 0 0 0 1.22 1.094");
}

.il7hh6whz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.25 16.618a6.55 6.55 0 0 0-6.549 6.548c0 7.371-4.588 10.13-5.272 10.13");
}

.jr-kjlewa {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.79 19.938c-1.946 0-3.066 1.77-3.066 3.54c0 6.206-3.449 11.754-5.464 12.448");
}

.lcbd-ac6c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.795 13.204a10.074 10.074 0 0 0-11.62 9.955c0 3.94-2.05 7.387-3.43 7.287");
}

.xyn1i7rxo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.77 10.393A13.6 13.6 0 0 0 5.65 23.53c0 2.526-1.15 3.409-1.15 3.409m23.47 8.972c0-3.43.154-2.167-3.714-6.273c-4.402-4.672-4.402-12.248 0-16.92s11.54-4.673 15.942 0s4.403 12.248 0 16.92c-3.867 4.106-3.717 2.883-3.717 6.274M32.228 19.11v4.457m5.345-5.884v1.81m-10.69-1.81v1.81");
}

</style>
