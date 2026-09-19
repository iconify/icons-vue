<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mekd_cbpt"/><g class="n1mjunbsu"><ellipse class="fh8tbib6r"/><ellipse class="l33gakbvv"/></g><g class="mrjy-p0fq"><ellipse class="l5g0o4y3j"/><ellipse class="amtzi-vsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:face-without-mouth" /></template>
<style>
.amtzi-vsr {
  cx: 42.812px;
  cy: 28.449px;
  rx: 4.201px;
  ry: 5.094px;
}

.fh8tbib6r {
  cx: 20.844px;
  cy: 28.449px;
  rx: 6.493px;
  ry: 9.727px;
}

.l33gakbvv {
  cx: 42.813px;
  cy: 28.449px;
  rx: 6.494px;
  ry: 9.727px;
}

.l5g0o4y3j {
  cx: 20.844px;
  cy: 28.449px;
  rx: 4.201px;
  ry: 5.094px;
}

.mekd_cbpt {
  fill: var(--svg-color--fbbf67, #fbbf67);
  d: path("M63.89 31.945c0 17.641-14.301 31.943-31.945 31.943C14.299 63.889 0 49.586 0 31.945C0 14.301 14.299 0 31.945 0C49.589 0 63.89 14.301 63.89 31.945");
}

.mrjy-p0fq {
  fill: var(--svg-color--25333a, #25333a);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

</style>
