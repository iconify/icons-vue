<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nhxdc3b-c"/><path class="brf5ppe_m"/><circle class="pqy74bbqa"/><circle class="upkkds57n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bluesecur" /></template>
<style>
.brf5ppe_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.28 14.525l6.979 6.746l-3.14 3.024V11.966l3.023 2.908l-6.862 6.978M5.5 34.127v4.93m3.267-4.93v4.93M5.5 36.53h3.267m7.508 2.527v-4.93h1.602c.925 0 1.664.739 1.664 1.663s-.74 1.665-1.664 1.665h-1.602m1.662-.001l1.543 1.542m1.977 0v-4.87l2.466 4.931l2.465-4.93v4.93m4.814-1.663h-2.22m-.554 1.663l1.664-4.93l1.665 4.93m7.476 0v-4.93l3.267 4.93v-4.93m-8.654 4.93v-4.93l3.267 4.93v-4.93m-24.623 4.93c-.925 0-1.603-.74-1.603-1.602V35.79c0-.925.74-1.665 1.603-1.665c.924 0 1.664.74 1.664 1.665v1.602c0 .925-.74 1.664-1.664 1.664");
}

.nhxdc3b-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.072 8.942h1.86c2.908 0 5.118 2.908 5.118 6.63v4.768c0 3.606-2.326 6.63-5.117 6.63h-1.861c-2.908 0-5.118-2.908-5.118-6.63v-4.768c-.116-3.722 2.21-6.63 5.118-6.63");
}

.pqy74bbqa {
  cx: 10.194px;
  cy: 33.015px;
  r: 0.75px;
  fill: currentColor;
}

.upkkds57n {
  cx: 14.789px;
  cy: 33.015px;
  r: 0.75px;
  fill: currentColor;
}

</style>
