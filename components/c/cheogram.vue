<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rxa0jvbkl"/><circle class="fg41y8bjd"/><circle class="shpv9_52k"/><circle class="azvc21bme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:cheogram" /></template>
<style>
.azvc21bme {
  cx: 32.977px;
  cy: 23.583px;
  r: 2.115px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fg41y8bjd {
  cx: 17.198px;
  cy: 23.583px;
  r: 2.115px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rxa0jvbkl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.499 15.494C39.283 7.74 29.747 3.63 20.459 5.566S4.568 14.97 4.501 23.615s6.423 16.2 15.68 18.252s18.857-1.936 23.191-9.637v.001l-4.59-2.505c-3.073 5.429-9.88 8.24-16.445 6.795s-11.167-6.772-11.12-12.867s4.732-11.36 11.318-12.725s13.349 1.533 16.34 6.999v-.001l4.625-2.434ZM10.058 36.502c2.044 3.206-.523 4.513-3.438 6.192c4.762.702 7.285-.382 9.172-2.295");
}

.shpv9_52k {
  cx: 25.17px;
  cy: 23.583px;
  r: 2.115px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
