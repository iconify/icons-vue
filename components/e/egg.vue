<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="j1q7yft4f"/><path class="su6z-2b8w"/><ellipse class="hj4dszbra"/><ellipse transform="rotate(-67.641 91.663 94.055)" class="k1w117nud"/><circle transform="rotate(-67.641 32.915 102.874)" class="qtl9ynbns"/><ellipse transform="rotate(-27.393 97.644 62.567)" class="g_pmmraag"/><ellipse transform="rotate(-27.393 68.517 89.407)" class="w3rb4qhti"/><ellipse transform="rotate(-51.427 64.797 104.317)" class="s6rcvobpk"/><ellipse transform="rotate(-48.356 52.394 107.013)" class="m4tvnabrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:egg" /></template>
<style>
.g_pmmraag {
  cx: 97.65px;
  cy: 62.57px;
  fill: var(--svg-color--d47858, #d47858);
  rx: 3.07px;
  ry: 2.7px;
}

.hj4dszbra {
  cx: 91.4px;
  cy: 43.58px;
  fill: var(--svg-color--d47858, #d47858);
  rx: 2.02px;
  ry: 2.06px;
}

.j1q7yft4f {
  fill: var(--svg-color--f2a05b, #f2a05b);
  d: path("M63.43 4.51c31.68-.07 51.67 51.46 43.78 84.12c-6.98 28.92-27.03 34.91-43.08 34.91s-35.54-7.78-43.08-33.79C12.33 59.63 33.87 4.58 63.43 4.51");
}

.k1w117nud {
  cx: 91.66px;
  cy: 94.05px;
  fill: var(--svg-color--d47858, #d47858);
  rx: 2.19px;
  ry: 2.18px;
}

.m4tvnabrh {
  cx: 52.39px;
  cy: 107.01px;
  fill: var(--svg-color--d47858, #d47858);
  rx: 3.58px;
  ry: 3.46px;
}

.qtl9ynbns {
  cx: 32.91px;
  cy: 102.87px;
  r: 2.04px;
  fill: var(--svg-color--d47858, #d47858);
}

.s6rcvobpk {
  cx: 64.79px;
  cy: 104.32px;
  fill: var(--svg-color--d47858, #d47858);
  rx: 3.23px;
  ry: 2.7px;
}

.su6z-2b8w {
  fill: var(--svg-color--fecc88, #fecc88);
  d: path("M39.26 29.03c-3.8 6.07-7.63 13.71-8.45 20.08c-1.5 11.73 7.13 13.05 10.14 7.23s6.09-11.71 10.98-19.52c6.76-10.79 17.83-18.02 12.39-22.71s-17.08 2.16-25.06 14.92");
}

.w3rb4qhti {
  cx: 68.52px;
  cy: 89.41px;
  fill: var(--svg-color--d47858, #d47858);
  rx: 3.07px;
  ry: 2.7px;
}

</style>
