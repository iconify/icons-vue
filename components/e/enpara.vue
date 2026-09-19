<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="l4_sd1_ea"/><path class="kgbm-0b5a"/><path class="ib9gro_iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:enpara" /></template>
<style>
.ib9gro_iv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.886 23.997c-1.254-4.935-3.695-8.411-6.787-11.558S28.927 6.483 24 5.125m.003 37.761c4.936-1.254 8.411-3.695 11.558-6.787s5.956-7.172 7.314-12.1m-37.761.004c1.254 4.936 3.695 8.411 6.787 11.558s7.172 5.956 12.1 7.314m-.004-37.761c-4.935 1.254-8.411 3.695-11.558 6.787S6.483 19.073 5.125 24");
}

.kgbm-0b5a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.705 28.784v-5.848c0-1.949-1.595-3.544-3.544-3.544s-3.544 1.595-3.544 3.544m0 5.848v-9.569m-5.765 7.617c-.532 1.064-1.772 1.772-3.013 1.772a3.554 3.554 0 0 1-3.544-3.544v-2.303c0-1.95 1.595-3.544 3.544-3.544s3.544 1.594 3.544 3.544v1.24h-7.088m28.591 0c-1.254-4.935-3.695-8.411-6.787-11.558S28.927 6.483 24 5.125");
}

.l4_sd1_ea {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.381 7.871c-8.858-3.67-19.907-3.67-28.765 0a3.34 3.34 0 0 0-1.743 1.743c-3.67 8.859-3.67 19.907 0 28.765a3.34 3.34 0 0 0 1.743 1.744c8.859 3.669 19.907 3.669 28.765 0a3.34 3.34 0 0 0 1.743-1.744c3.67-8.858 3.67-19.907 0-28.765a3.34 3.34 0 0 0-1.743-1.743");
}

</style>
