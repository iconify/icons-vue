<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wso-iqbhz"/><circle class="lt-9jcbov"/><circle class="p8915rvyx"/><path class="gt2r76bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:confirmtkt" /></template>
<style>
.gt2r76bag {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.908 7.4a3.165 3.165 0 0 0-3.147-2.9h-7.522a3.165 3.165 0 0 0-3.147 2.9c-3.516.498-6.223 3.512-6.223 7.166v15.688c0 1.203.785 2.213 1.868 2.574l-.605 2.364a.556.556 0 0 0 .42.681L24 38.383l11.448-2.51a.556.556 0 0 0 .42-.681l-.604-2.364a2.72 2.72 0 0 0 1.867-2.575V14.567c0-3.654-2.706-6.668-6.222-7.166Zm3.922 36.1l-2.165-5.011m-17.33 0L13.17 43.5m1.452-3.361h18.752");
}

.lt-9jcbov {
  cx: 16.591px;
  cy: 29.671px;
  r: 2.027px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.p8915rvyx {
  cx: 31.409px;
  cy: 29.667px;
  r: 2.027px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wso-iqbhz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.266 9.149h7.468m2.853 14.596H17.413l-2.562-8.979h18.298z");
}

</style>
