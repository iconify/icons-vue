<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><path id="SVGHApfZLGh" class="hxrtby_tr"/></defs><use href="#SVGHApfZLGh" class="c-zrgpb5l"/><use href="#SVGHApfZLGh" class="c-zrgpb5l"/><path class="dxzleiz0z"/><path class="njlmrvbff"/><circle class="fqhrnjbrb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anycode-wallet" /></template>
<style>
.c-zrgpb5l {
  stroke-linecap: round;
  stroke-linejoin: round;
}

.dxzleiz0z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.959 32.052v5.968h-1.918v-5.968m1.918-8.311v-5.967h-1.918v5.967m-23.656-5.967h1.918V38.02h-1.918zm-3.836 0V38.02m9.484-20.246V38.02m2.877-20.246h1.918V38.02H20.91zm7.672 0V38.02h-1.918V17.774zm3.836 14.172v6.074m0-20.246v6.074m-15.516-9.443l18.82-7.394c1.065-.426 2.344.32 2.77 1.492l2.135 6.254M33.27 31.946h8.099a2.137 2.137 0 0 0 2.131-2.131v-3.73a2.137 2.137 0 0 0-2.131-2.13H33.27a2.137 2.137 0 0 0-2.13 2.13v3.73c0 1.172.958 2.13 2.13 2.13");
}

.fqhrnjbrb {
  cx: 35.402px;
  cy: 27.897px;
  r: 1.598px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hxrtby_tr {
  fill: none;
  stroke: currentColor;
  d: path("M41.262 31.946v7.459c0 .959-.852 1.705-1.918 1.705H6.418c-1.066 0-1.918-.746-1.918-1.705V16.388c0-.959.852-1.705 1.918-1.705h32.926c1.066 0 1.918.746 1.918 1.705v7.46");
}

.njlmrvbff {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.107 23.848H32.95c-1.066 0-1.918.959-1.918 2.13v3.73c0 1.172.852 2.131 1.918 2.131h8.631c1.066 0 1.918-.959 1.918-2.13v-3.73c0-1.172-.853-2.131-1.918-2.131z");
}

</style>
