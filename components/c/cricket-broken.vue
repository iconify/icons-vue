<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xj18tnblb"/><path class="yd1rzjlwy"/><path class="rnktkkbmm"/><path class="g_k8_n5_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cricket-broken" /></template>
<style>
.g_k8_n5_k {
  d: path("M16.4785 16.0313C18.7584 17.1112 19.3584 17.7112 20.4383 19.9911");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rnktkkbmm {
  d: path("M21.2582 18.0112C21.2582 19.5576 20.0046 20.8112 18.4582 20.8112C16.9118 20.8112 15.6582 19.5576 15.6582 18.0112C15.6582 16.4648 16.9118 15.2112 18.4582 15.2112C20.0046 15.2112 21.2582 16.4648 21.2582 18.0112Z");
}

.xj18tnblb {
  d: path("M10.3101 17.0834L7.50821 19.8853C6.59181 20.8017 5.29351 20.7253 4.30071 19.7325L3.53712 18.9689C2.54432 17.9761 2.46791 16.6778 3.38432 15.7614L11.5557 7.59007C12.243 6.90277 12.7775 6.67367 13.5412 6.67367H15.2213L18.3524 3.54257C18.8106 3.08437 19.4215 3.08437 19.8034 3.46617C20.1852 3.84807 20.1852 4.45897 19.727 4.91717L16.5959 8.04827V9.72837C16.5959 10.4921 16.3668 11.0266 15.6795 11.7139L12.7142 14.6792");
}

.yd1rzjlwy {
  d: path("M15.3746 7.89563L8.6543 14.6159");
}

</style>
