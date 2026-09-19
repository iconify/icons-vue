<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kwp1agbjb"/><path class="wxqbfhz-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:borrowbox" /></template>
<style>
.kwp1agbjb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.778 28.101c-1.624-1.068-3.26-2.209-6.14-1.093c-2.156 1.003-4.044 1.88-6.138 1.093V12.577c2.252.408 4.226-.228 6.139-1.093c2.231-1.07 4.25-.49 6.139 1.093c1.889-1.583 3.907-2.163 6.139-1.093c1.912.865 3.886 1.501 6.139 1.093v15.524c-2.095.786-4.153-.385-6.14-1.093c-2.936-.911-4.514.025-6.138 1.093");
}

.wxqbfhz-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m11.814 42.457l.005-8.597C8.157 32.95 5.5 29.528 5.5 25.587V13.863a8.3 8.3 0 0 1 8.32-8.32h20.36a8.3 8.3 0 0 1 8.32 8.32v11.724a8.3 8.3 0 0 1-8.32 8.32l-12.825-.002z");
}

</style>
