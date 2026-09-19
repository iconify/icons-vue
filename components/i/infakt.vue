<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="s965h92_q"/><path class="w459e1b-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:infakt" /></template>
<style>
.s965h92_q {
  cx: 33.036px;
  cy: 11.494px;
  r: 6.994px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.w459e1b-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.117 9.4c.005-.072-3.732 3.342 2.255 7.956c-2.414 4.293 1.881 6.376 1.881 6.376c-2.145 4.005 3.072 5.978 3.072 5.978c-2.21 5.092-4.416 9.976-7.851 13.755c3.3.194 4.506-.417 6.404-1.798c7.476-5.44 10.9-13.792 12.729-18.373c.851-2.133-.712-5.261-2.752-6.316C19.29 14.102 9.004 9.463 9.117 9.4");
}

</style>
