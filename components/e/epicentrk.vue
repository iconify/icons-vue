<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="tk35jpxmc"/><path class="aeale8bce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:epicentrk" /></template>
<style>
.aeale8bce {
  d: path("M18.202 30.771c-5.844-10.713-5.844-9.74 5.843-9.74s11.688-.973 5.844 9.74c0 0-4.87 8.766-5.844 8.766s-5.843-8.766-5.843-8.766m4.87-10.234v-1.453c0-.974-.974-1.948-.974-1.948V5.448c0-1.948 1.222-1.948 1.948-1.948s1.947 0 1.947 1.948v11.688s-.974.974-.974 1.948v1.453");
}

.tk35jpxmc {
  cx: 24px;
  cy: 27.439px;
  r: 17.061px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
