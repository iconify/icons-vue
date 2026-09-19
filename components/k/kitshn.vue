<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="dma1v4bvc"/><path class="yylvecq0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kitshn" /></template>
<style>
.dma1v4bvc {
  d: path("M24.877 11.616c-.94 1.86-3.052 4.19-4.831 6.655m.005 10.098q3.973.238 9.502-.146l3.565-.596l4.172-1.47");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yylvecq0j {
  d: path("M36.175 27.883v11.9H13.387v-11.9c-2.042-2.187-5.227-3.786-6.83-6.71c-2.042-3.728-1.025-7.983 2.183-10.676a9.64 9.64 0 0 1 5.96-2.273q3.221-.105 6.051 1.429c1.312.71 2.59 1.837 4.126 1.963c1.733.141 3.066-.806 4.675-1.531c4.374-1.972 9.537-.98 11.919 3.14c2.028 3.508.846 8.05-1.695 10.824c-1.228 1.34-3.108 2.045-3.601 3.834");
}

</style>
