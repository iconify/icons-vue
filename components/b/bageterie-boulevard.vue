<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nsswaobtf"/><path class="fv1hpab7e"/><path class="h_q-gbc_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bageterie-boulevard" /></template>
<style>
.fv1hpab7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.75 21.506l-.591 18.17c9.747 1.516 11.46-9.844.636-9.844c8.287.549 11.065-9.05-.044-8.327");
}

.h_q-gbc_k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.013 6.984L11.93 31.67l6.921-.064l-.078 11.007l18.007.886l1.207-25.732l-9.11-1.154L27.97 4.5z");
}

.nsswaobtf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m15.665 9.645l1.076 18.73c10.16.655 10.865-11.179-.258-10.176c8.568-.204 10.533-10.327-.818-8.554");
}

</style>
