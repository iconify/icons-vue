<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="htrg_8bya"/><g class="rm3lzbu0r"><path class="qedo2sb9y"/><circle class="hn9ngacgu"/></g><path class="fkp4q9bgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:digital-clock" /></template>
<style>
.fkp4q9bgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.105 27.336c.6.5 1.1.7 2.5.7h.3c1.1 0 2-.9 2-2s-.9-2-2-2m-2.8-3.316c.6-.5 1.2-.7 2.5-.7h.3c1.1 0 2 .9 2 2s-.9 2-2 2m-1.5.016h1.5");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.hn9ngacgu {
  cx: 23.82px;
  cy: 21.3px;
  r: 0.75px;
}

.htrg_8bya {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.732 22.607c0-1.6 1.5-2.9 3.2-2.6c1.1.2 2 1.2 2.1 2.3c0 .8-.2 1.7-.8 2.2c-1.1.9-4.5 3.5-4.5 3.5h5.3m17.366-6.987l-3.945 6.016m2 .9zc-1.5 0-2.7-1.2-2.7-2.6v-2.7c0-1.5 1.2-2.6 2.6-2.6c1.5 0 2.6 1.2 2.6 2.6v2.7c.2 1.5-1 2.6-2.5 2.6m9.239-6.916l-3.945 6.016m2 .9zc-1.5 0-2.7-1.2-2.7-2.6v-2.7c0-1.5 1.2-2.6 2.6-2.6c1.5 0 2.6 1.2 2.6 2.6v2.7c.2 1.5-1 2.6-2.5 2.6");
}

.qedo2sb9y {
  d: path("M24.57 26.7a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0");
}

.rm3lzbu0r {
  fill: currentColor;
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

</style>
