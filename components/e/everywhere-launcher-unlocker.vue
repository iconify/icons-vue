<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="f_v_dfbgn"/><path class="lwkk92ift"/><circle class="yut2ubb3v"/><path class="jhvxirisz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:everywhere-launcher-unlocker" /></template>
<style>
.f_v_dfbgn {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
}

.jhvxirisz {
  d: path("M41.31 18.056v-2.101m-3.712.085l-.004-.12a1.859 1.859 0 1 1 3.718 0h0c0 .04.002.128 0 .168");
}

.lwkk92ift {
  d: path("M2.586 22.834H26.73v2.945H2.627m1.812-10.095h22.294v2.945H3.363M9.37 8.539h17.352v2.944H6.686M3.72 29.973h23.002v2.944H4.972m2.364 4.194h19.391v2.945H9.806M28.78 8.529v2.957m2.07-2.96v2.957m-2.066 4.2v2.958m2.069-2.961v2.958m-2.076 4.203v2.957m2.07-2.959v2.957m-2.059 4.171v2.957m2.07-2.96v2.957m-2.074 4.196v2.957m2.069-2.96v2.957m13.261-9.902H33.357v-12.03H44.29");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yut2ubb3v {
  cx: 39.451px;
  cy: 24.197px;
  r: 1.859px;
}

</style>
