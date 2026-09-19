<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v3ofcbx_d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:e-amusement" /></template>
<style>
.v3ofcbx_d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.181 29.536c-7.22 21.092-32.022 16.36-30.276-1.354C12.152-4.775 47.28.2 34.216 21.579c-10.142 16.597-22.458 6.895-17.25-2.125");
}

</style>
