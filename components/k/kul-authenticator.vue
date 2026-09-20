<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nn151c42m"/><path class="o0ozng7_p"/><path class="xf_90t-qk"/><path class="uk3lodvry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kul-authenticator" /></template>
<style>
.nn151c42m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.393 26.472L29.01 41.21l-.732 1.29l-5-2.515l-4.047-14.158");
}

.o0ozng7_p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.393 26.472c-6.605.37-12.467-3.46-11.261-11.166");
}

.uk3lodvry {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m29.337 19.411l12.554 11.947l.05 2.497l-5.634.03l-10.95-10.738m-.013.005a7.112 7.112 0 0 1-9.601-6.661a7.111 7.111 0 0 1 14.222 0a7.1 7.1 0 0 1-.623 2.91");
}

.xf_90t-qk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.675 19.277a7.41 7.41 0 1 1 11.133-5.334");
}

</style>
