<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="owp4d4b5z"/><circle class="l-c4e9kpv"/><path class="v3pw2p0of"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:airlift" /></template>
<style>
.l-c4e9kpv {
  cx: 30.455px;
  cy: 20.784px;
  r: 0.75px;
  fill: currentColor;
}

.owp4d4b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M14.865 22.813v-1.54a8.036 8.036 0 0 1 8.013-8.013h0a8.04 8.04 0 0 1 7.32 4.763M8.108 34.69h0A3.62 3.62 0 0 1 4.5 31.081v-2.103a3.62 3.62 0 0 1 3.608-3.608h0a3.62 3.62 0 0 1 3.607 3.608v2.103a3.62 3.62 0 0 1-3.607 3.607Zm3.607-9.319v9.318m3.282-9.318v9.318m15.458-10.457v10.457m-12.132-9.318v9.318m0-6.279a3.62 3.62 0 0 1 3.608-3.607h0a3.7 3.7 0 0 1 .723.073m5.088 9.81l-.133.003h-.214a2.5 2.5 0 0 1-2.495-2.494v-12.1");
}

.v3pw2p0of {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.18 34.74V22.742a2.545 2.545 0 0 1 2.545-2.544h0a5 5 0 0 1 .823.063m2.589 1.846v10.815a1.82 1.82 0 0 0 1.818 1.817h.545m-10.451-9.633h9.997");
}

</style>
