<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="xco-krb2l"/><path class="uxjwr_bny"/><path class="sxnbaccxp"/><path class="cj_kg3lmx"/><path class="a0z5yuksy"/><path class="k0yg2-byv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:k-powerpay" /></template>
<style>
.a0z5yuksy {
  d: path("M13.413 38.757c1.069-.506 2.105-1.017 3.587-.997c2.913.04 3.92 1.97 7 1.97s4.088-1.93 7-1.97c1.482-.02 2.518.49 3.587.997");
}

.cj_kg3lmx {
  d: path("M10.41 36.048c2.657-.239 3.877-1.98 6.59-1.944c2.913.04 3.92 1.97 7 1.97s4.088-1.93 7-1.97c2.713-.036 3.933 1.705 6.59 1.944m-22.443 3.811a5.9 5.9 0 0 1 1.853-.27c2.913.039 3.92 1.97 7 1.97s4.088-1.931 7-1.97c.7-.01 1.301.099 1.853.27");
}

.k0yg2-byv {
  d: path("M11.915 37.559c1.728-.572 2.94-1.656 5.085-1.627c2.913.04 3.92 1.97 7 1.97s4.088-1.93 7-1.97c2.146-.029 3.358 1.055 5.085 1.627");
}

.sxnbaccxp {
  d: path("M34.357 15.893v7.29c0 1.272-.459 2.793-1.515 3.5l-4.537 3.042c-1.36.911-2.66 1.615-2.66 3.539v1.264v-6.187c0-2.065-.175-4.153 2.21-5.556");
}

.uxjwr_bny {
  d: path("M22.418 34.528V20.926c0-1.306.072-2.372-1.5-3.62l-4.306-3.42c-2.882-2.287-3.317-4.378-3.317-4.378v6.762c0 1.86.86 3.004 2.448 4.158l3.414 2.485c3.059 2.226 3.233 4.658 3.261 8.637m1.648 2.978V20.926c0-1.306-.303-2.48 1.504-3.68l5.153-3.416c3.395-2.252 3.634-4.322 3.634-4.322v6.385c0 2.516-1.498 3.705-3.295 4.85l-3.207 2.043c-3.463 2.205-3.79 2.498-3.79 8.764");
}

.xco-krb2l {
  d: path("M45.5 24c0 11.884-9.616 21.5-21.5 21.5S2.5 35.883 2.5 24S12.117 2.5 24 2.5S45.5 12.117 45.5 24");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
