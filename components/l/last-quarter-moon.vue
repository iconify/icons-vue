<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nnxm7ygvz"/><path class="v5f91jbhv"/><circle class="wly9_qq7h"/><path class="yuh-fabri"/><g class="ed4r-5bxj"><path class="qp6igkfjf"/><circle class="alsx51bjv"/></g><circle class="ju6csibnz"/><path class="t305e4bwe"/><path class="gisyy_s2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:last-quarter-moon" /></template>
<style>
.alsx51bjv {
  cx: 57.757px;
  cy: 18.918px;
  r: 2.195px;
}

.ed4r-5bxj {
  fill: var(--svg-color--4f6977, #4f6977);
}

.gisyy_s2k {
  fill: var(--svg-color--e0cf35, #e0cf35);
  d: path("M16.339 11.08a4.835 4.835 0 1 0 9.669-.005a4.835 4.835 0 0 0-9.669.005");
}

.ju6csibnz {
  cx: 7.839px;
  cy: 32.896px;
  r: 2.195px;
  fill: var(--svg-color--e0cf35, #e0cf35);
}

.nnxm7ygvz {
  fill: var(--svg-color--405866, #405866);
  d: path("M32.07 64c17.604 0 31.875-14.27 31.875-31.875C63.945 14.521 49.674.25 32.07.25");
}

.qp6igkfjf {
  d: path("M54.26 36.542a3.847 3.847 0 0 0 7.692 0a3.846 3.846 0 1 0-7.692 0");
}

.t305e4bwe {
  fill: var(--svg-color--4f6977, #4f6977);
  d: path("M43.1 19.656a3.434 3.434 0 1 0 6.867 0a3.434 3.434 0 0 0-6.867 0");
}

.v5f91jbhv {
  fill: var(--svg-color--f5eb35, #f5eb35);
  d: path("M32 64C14.396 64 .125 49.73.125 32.125S14.396.249 32 .249");
}

.wly9_qq7h {
  cx: 44.736px;
  cy: 49.03px;
  r: 9.226px;
  fill: var(--svg-color--4f6977, #4f6977);
}

.yuh-fabri {
  fill: var(--svg-color--e0cf35, #e0cf35);
  d: path("M22.16 24.488a3.919 3.919 0 0 0 7.836 0a3.917 3.917 0 0 0-3.915-3.916a3.92 3.92 0 0 0-3.921 3.916M13.384 48.37a3.84 3.84 0 0 0 7.678 0a3.836 3.836 0 0 0-3.834-3.833a3.84 3.84 0 0 0-3.844 3.833");
}

</style>
