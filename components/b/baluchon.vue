<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffy5_43mc"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:baluchon" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ffy5_43mc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.133 25.996c-.817 2.418-3.648 4.201-7.014 4.201c-4.005 0-7.252-2.524-7.252-5.637s3.247-5.638 7.252-5.638c3.03 0 5.626 1.445 6.71 3.497m-6.242 7.811v3.64m0-15.362V14.13");
}

</style>
