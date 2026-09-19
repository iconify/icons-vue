<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cf4ko4byy"/><path class="u1my2kb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ampereflow" /></template>
<style>
.cf4ko4byy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.505 8.5v-3a1 1 0 0 1 1-1h6.67a1 1 0 0 1 1 1v3m0 0h4.63a2 2 0 0 1 2 2v31a2 2 0 0 1-2 2h-17.61a2 2 0 0 1-2-2v-31a2 2 0 0 1 2-2h4.31m-.005 0h8.67");
}

.u1my2kb9o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m25.359 21.06l-4.268 6.316h5.817l-4.267 6.317M24 16.102v2.248m-3.484-1.406l.969 1.779m6-1.779l-.97 1.779");
}

</style>
