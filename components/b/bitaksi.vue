<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o5lfegbzc"/><circle class="nlp3aiksm"/><path class="d3jrmkwki"/><circle class="vaepkabys"/><path class="chbc4ub2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bitaksi" /></template>
<style>
.chbc4ub2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.728 23.41A4.22 4.22 0 0 0 5.5 27.64v5.286a4.22 4.22 0 0 0 4.228 4.229h5.33c4.741 2.032 6.797 2.065 9.114 2.065c2.53 0 4.657-.07 8.84-2.065h5.26a4.22 4.22 0 0 0 4.228-4.229V27.64a4.22 4.22 0 0 0-4.229-4.229zM25.381 9.34V7.507H22.7v1.856");
}

.d3jrmkwki {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.77 23.367l4.431-9.515c2.847-5.98 16.982-6.162 19.57 0l4.54 9.515");
}

.nlp3aiksm {
  cx: 11.355px;
  cy: 30.767px;
  r: 2.114px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o5lfegbzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.24 37.195s-.183 1.35 0 2.03c.129.473.251 1.268.74 1.268h2.75c.489 0 .611-.796.74-1.268c.183-.68 0-2.03 0-2.03m21.142.029s-.184 1.32 0 2c.128.473.25 1.27.74 1.27h2.749c.49 0 .612-.797.74-1.27c.184-.68 0-2.063 0-2.063");
}

.vaepkabys {
  cx: 36.726px;
  cy: 30.767px;
  r: 2.114px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
