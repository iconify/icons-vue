<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b0qeydb9h"/><path class="se4q3jbcj"/><path class="dq6cj2b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kwsp-i-akaun" /></template>
<style>
.b0qeydb9h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.863 5.337V16.26a3.5 3.5 0 0 1-3.494 3.506H3.114h9.244a3.5 3.5 0 0 1 3.505 3.494v19.403");
}

.dq6cj2b1v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.496 27.438h5.488c1.382 0 3.357-.289 3.807-2.172c.896-3.742-4.767-8.502-6.997-9.398");
}

.se4q3jbcj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M3.114 19.766v-.847L8.503 14.2v21.27m15.909-25.29v22.953c0 1.619-1.025 2.922-2.297 2.922s-2.297-1.303-2.297-2.922V19.154v13.629a3.265 3.265 0 0 1-3.259 3.272h-1.375a3.265 3.265 0 0 1-3.272-3.257v-7.949m25.706-10.053v25.156m-9.68-3.652c-.897.629-2.183 1.461-3 2.124c-1.309 1.06-.67 3.644 1.261 3.487c1.884-.153 3.442-1.366 4.77-2.275c2.518-1.724 4.016-3.45 2.911-5.62l-5.779-15.444c-.873-2.998 1.132-4.447 3.568-6.473c1.837-1.527 5.947-3.995 5.947-1.929v1.382");
}

</style>
