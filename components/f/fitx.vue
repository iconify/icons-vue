<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sid7dxlcv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fitx" /></template>
<style>
.sid7dxlcv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.11 24.062l10.308 10.565c-3.147 2.755-7.491 4.829-12.495 5.83l-6.913-7.078l-6.923 7.088c-5.004-1.001-9.358-3.065-12.505-5.83L14.91 24.062L4.5 13.404c3.126-2.765 7.46-4.86 12.464-5.87l7.046 7.211l7.037-7.212c4.993 1.022 9.327 3.116 12.453 5.881z");
}

</style>
