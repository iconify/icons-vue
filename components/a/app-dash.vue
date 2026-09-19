<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ty_e5jdlc"/><path class="a_6y8dtiu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:app-dash" /></template>
<style>
.a_6y8dtiu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.194 42.5V24L42.5 30.167V42.5zm-4.111-28.778V5.5L14.75 12.694v10.278M16.806 42.5h5.138");
}

.ty_e5jdlc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.806 42.5V21.944L5.5 28.111V42.5zM33.25 25.028v-14.39l-11.306 6.168V42.5h9.25");
}

</style>
