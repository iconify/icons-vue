<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ur_ue9otv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:4ka-slovakia" /></template>
<style>
.ur_ue9otv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.017 11.916H36.83m-1.037 3.131l3.13-9.45l3.131 9.45M28.527 5.5v9.45m0-3.291l5.079-6.127m0 9.418l-3.891-4.725M6.002 28.31L19.057 8.091L24.07 11L12.187 28.2v6.3l-6.24.039zm10.09.586h6.691l-.079-7.012h5.8v6.946l6.85.009v5.697h-7.008V42.5h-5.602l.01-7.899l-6.674-.02z");
}

</style>
