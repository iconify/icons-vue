<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><ellipse class="yvitd_80y"/><path class="f_2n5mbuv"/><path class="d5bqefb8v"/><path class="d30yyrbxh"/><path class="fwp34bi0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fairtiq" /></template>
<style>
.d30yyrbxh {
  d: path("M26.19 33.111a5.56 5.56 0 0 1 .792-5.878c1.378-1.661 3.598-2.438 5.754-2.013");
}

.d5bqefb8v {
  d: path("M32.086 39.562c-8.172 4.869-18.666 3.03-24.704-4.329c-6.039-7.358-5.812-18.032.532-25.127S24.821 1.62 32.78 6.83s10.928 15.465 6.991 24.137m3.197 3.143c2.422 2.07 2.72 5.672.672 8.104s-5.691 2.802-8.2.834");
  opacity: var(--svg-opacity--0-97, 0.97);
}

.f_2n5mbuv {
  d: path("M26.19 33.098c-4.518 1.793-9.664.26-12.5-3.724a10.83 10.83 0 0 1 .48-13.166a10.54 10.54 0 0 1 12.737-2.785c4.376 2.124 6.77 6.977 5.817 11.789");
  opacity: var(--svg-opacity--0-97, 0.97);
}

.fwp34bi0y {
  d: path("m32.864 25.25l10.153 8.898m-16.884-1.145l9.182 9.886");
  opacity: var(--svg-opacity--0-97, 0.97);
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yvitd_80y {
  cx: 38.915px;
  cy: 38.239px;
  opacity: var(--svg-opacity--0-97, 0.97);
  rx: 2.869px;
  ry: 2.798px;
}

</style>
