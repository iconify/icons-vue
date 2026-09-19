<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="hk0kfibub"/><path class="q2bh4fb9y"/></g><g class="y9tr6bcfx"><path class="u7-ckq-hy"/><path class="ibg_afdgr"/><path class="mmzn1gsij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bubble-translate" /></template>
<style>
.hk0kfibub {
  d: path("m6.215 16.795l20.12 11.592c1.388.799 3.074 1.649 4.76.658l10.51-6.173c.852-.5 1.392-1.568.221-2.243L21.706 9.038c-1.388-.8-3.074-1.65-4.76-.659l-10.51 6.173c-1.153.678-1.258 1.646-.22 2.243m20.911 1.063l-4.608 2.62");
}

.ibg_afdgr {
  d: path("m11.747 19.982l-5.31 3.12c-1.154.677-1.259 1.645-.222 2.242h0l20.12 11.591c1.388.8 3.074 1.65 4.76.66l10.51-6.174c.47-.277.846-.726.89-1.187");
}

.mmzn1gsij {
  d: path("M5.5 24.342v2.043c0 .364.242.713.479.85l20.357 11.727c1.387.8 3.073 1.65 4.759.659l10.51-6.173c.469-.276.89-.72.89-1.182l-.001-2.031m0-.192c-.034-.31-.233-.614-.668-.865l-5.53-3.186");
}

.q2bh4fb9y {
  d: path("m25.075 23.238l-7.53-8.2l14.441 4.27");
}

.u7-ckq-hy {
  d: path("m16.886 26.808l3.213-2.015m6.196 3.57a6.3 6.3 0 0 1-1.203 4.04m-6.715-6.43c2.119 1.013 4.53 1.597 6.93 1.823");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
