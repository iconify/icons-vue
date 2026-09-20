<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wdt8s1baf"/><path class="rmkygjd_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:edt-univ" /></template>
<style>
.rmkygjd_q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.34 10.62a2.36 2.36 0 0 0 2.36 2.36a2.36 2.36 0 0 0 2.36-2.36V6.86A2.36 2.36 0 0 0 32.7 4.5a2.36 2.36 0 0 0-2.36 2.36Zm-17.4 0za2.36 2.36 0 0 0 2.36 2.36a2.36 2.36 0 0 0 2.36-2.36V6.86A2.36 2.36 0 0 0 15.3 4.5a2.36 2.36 0 0 0-2.36 2.36Zm-.44 22.843h23m-23 5.746h23m-23-11.493h23m-23-5.746h23m0 17.239V21.97m-5.737 17.239V21.97m-5.736 17.239V21.97m-5.79 17.25V21.981M12.5 39.209V21.97");
}

.wdt8s1baf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.66 8.74h12.68m4.72 0h4.44a1.88 1.88 0 0 1 1.88 1.88v31a1.88 1.88 0 0 1-1.88 1.88h-31a1.88 1.88 0 0 1-1.88-1.88v-31A1.88 1.88 0 0 1 8.5 8.74h4.44m-6.32 8.95h34.76");
}

</style>
