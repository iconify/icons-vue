<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yk_z59p_h"/><path class="zs77tib_t"/><path class="nz-tk1bcg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:filter-color" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nz-tk1bcg {
  d: path("M14 14.75h7.25l-2.75 3.5v3l-1.75-1v-2Z");
}

.yk_z59p_h {
  d: path("M13.933 11.909C13.307 7.838 8.5 3.25 8.5 3.25S3 8.5 3 12.75q0 .135.007.27q.006.135.019.269q.014.134.034.268q.019.134.046.266q.026.132.059.263t.072.261t.085.256q.045.127.097.252q.051.124.109.247q.058.122.121.241q.064.119.133.235q.07.115.145.228q.075.112.155.22q.081.109.166.213q.086.105.177.205q.09.1.186.195q.095.096.195.186q.1.091.205.177t.213.166t.22.155q.113.075.228.145q.116.069.235.133q.119.063.241.121q.123.058.247.109q.125.052.252.097t.256.085t.261.072t.263.059t.266.046q.134.02.268.034q.134.013.269.019q.135.007.27.007q.5 0 .991-.09q.492-.09.959-.267t.895-.436q.428-.258.802-.59");
}

.zs77tib_t {
  fill: currentColor;
  d: path("M12.144 16.87q-.374.331-.802.589q-.427.258-.894.434q-.467.177-.958.267t-.99.09v-15s4.81 4.591 5.434 8.662");
}

</style>
