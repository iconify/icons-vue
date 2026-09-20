<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="cys61rbnf"/><path class="bx_mfcbkw"/><path class="qtcmuw83j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:izipay-ya" /></template>
<style>
.bx_mfcbkw {
  d: path("M22.07 24.433v5.656a4.19 4.19 0 0 1-4.19 4.19a4.18 4.18 0 0 1-2.963-1.227");
}

.cys61rbnf {
  d: path("M8.51 11.59L39.49 5.5v30.91L8.51 42.5z");
}

.qtcmuw83j {
  d: path("M22.07 17.519v6.913a4.19 4.19 0 1 1-8.38 0V17.52m20.548 6.913a4.19 4.19 0 1 1-8.38 0v-2.724a4.19 4.19 0 1 1 8.38 0m-.001 6.913V17.519");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
