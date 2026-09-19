<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sl4ekoghj"/><path class="ukdrnccrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:autenticacao-gov" /></template>
<style>
.sl4ekoghj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 37c-7.18 0-13-5.82-13-13s5.82-13 13-13V2.5C12.126 2.5 2.5 12.126 2.5 24S12.126 45.5 24 45.5z");
}

.ukdrnccrp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 19.206h4.879v4.458a2.44 2.44 0 0 1-2.44 2.439h0A2.44 2.44 0 0 1 24 23.663zm6.879 0h4.878v4.458a2.44 2.44 0 0 1-2.44 2.439h0a2.44 2.44 0 0 1-2.438-2.44zm0-8.898h4.878v4.458a2.44 2.44 0 0 1-2.44 2.44h0a2.44 2.44 0 0 1-2.438-2.44zm0 17.795h4.878v4.458A2.44 2.44 0 0 1 33.317 35h0a2.44 2.44 0 0 1-2.438-2.44zm6.878-8.897h4.879v4.458a2.44 2.44 0 0 1-2.44 2.439h0a2.44 2.44 0 0 1-2.439-2.44z");
}

</style>
