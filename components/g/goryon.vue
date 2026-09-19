<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="yuphw16gn"/><path class="fqzi9s6zv"/><ellipse class="hkwlbdcgn"/><circle class="xb_4lwbam"/><ellipse class="k62t6sq7f"/><circle class="alk137y3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:goryon" /></template>
<style>
.alk137y3m {
  cx: 30.209px;
  cy: 26.143px;
  r: 1.191px;
}

.fqzi9s6zv {
  d: path("m28.702 33.73l-4.513 8.066l-4.737-7.937z");
}

.hkwlbdcgn {
  cx: 16.822px;
  cy: 25.053px;
  rx: 4.728px;
  ry: 4.723px;
}

.k62t6sq7f {
  cx: 31.094px;
  cy: 25.053px;
  rx: 4.728px;
  ry: 4.723px;
}

.xb_4lwbam {
  cx: 17.706px;
  cy: 26.143px;
  r: 1.191px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yuphw16gn {
  d: path("m20.925 3l-2.545 8.488l-.207.07l-5.898-7.897s1.177 6.291 1.775 9.672c-5.386 3.145-8.651 8.616-8.655 14.497C5.395 37.313 13.724 45 24 45h0c10.275 0 18.605-7.686 18.605-17.168v-.002c-.003-7.059-4.687-13.397-11.808-15.975L32.64 7.95l-4.144 3.22a20 20 0 0 0-2.475-.403l-1.148-5.499l-1.984 5.468q-.15.008-.298.018z");
}

</style>
