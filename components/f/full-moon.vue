<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="ta0btrmdc"/><g class="eyuj09bzi"><circle class="se88hdc9r"/><path class="tn6yhibkh"/><circle class="ct_5_ub0m"/><circle class="kdp35gbbt"/><path class="cdoo82kgk"/><circle class="zd6o3zbnr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:full-moon" /></template>
<style>
.cdoo82kgk {
  d: path("M20.967 19.656a3.433 3.433 0 1 1-6.866 0a3.433 3.433 0 0 1 6.866 0");
}

.ct_5_ub0m {
  cx: 5.967px;
  cy: 36.54px;
  r: 3.845px;
}

.eyuj09bzi {
  fill: var(--svg-color--e0cf35, #e0cf35);
}

.kdp35gbbt {
  cx: 6.313px;
  cy: 18.917px;
  r: 2.195px;
}

.se88hdc9r {
  cx: 29.32px;
  cy: 53.02px;
  r: 9.226px;
}

.ta0btrmdc {
  cx: 32px;
  cy: 32.12px;
  r: 31.875px;
  fill: var(--svg-color--f5eb35, #f5eb35);
}

.tn6yhibkh {
  d: path("M41.904 24.487a3.918 3.918 0 1 1-7.836-.002a3.918 3.918 0 0 1 7.836.002");
}

.zd6o3zbnr {
  cx: 42.896px;
  cy: 11.07px;
  r: 4.835px;
}

</style>
