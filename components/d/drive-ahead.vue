<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="e9-ebdp8j"/><path class="d0b-cbu_i"/></g><g class="y9tr6bcfx"><path class="qsdgmbbbv"/><path class="ecd7-dx3b"/></g><g class="y9tr6bcfx"><path class="pcamfrbaw"/><path class="mmcv-c20d"/></g><g class="y9tr6bcfx"><path class="ac6gmnb8l"/><path class="o8yu281-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:drive-ahead" /></template>
<style>
.ac6gmnb8l {
  d: path("m20.093 12.397l-3.213 3.529l-2.554-.103l-1.418-1.33l.026-2.26l1.776-1.88l2.115-.1l.98.957l.954-.168z");
}

.d0b-cbu_i {
  d: path("M39.51 20.66a3.493 3.493 0 1 1-6.985 0a3.493 3.493 0 0 1 6.986 0");
}

.e9-ebdp8j {
  d: path("M43.5 20.66a7.48 7.48 0 0 1-7.482 7.478c-4.133 0-7.483-3.348-7.483-7.478s3.35-7.479 7.483-7.479A7.48 7.48 0 0 1 43.5 20.66");
}

.ecd7-dx3b {
  d: path("M20.62 32.875a3.493 3.493 0 0 1-3.492 3.493h0a3.493 3.493 0 0 1-3.493-3.493h0a3.493 3.493 0 0 1 3.493-3.493h0a3.493 3.493 0 0 1 3.493 3.493");
}

.mmcv-c20d {
  d: path("m17.623 19.28l-5.438-3.38l-6.25 8.002");
}

.o8yu281-a {
  d: path("m16.825 10.253l-1.981 2.09l1.085.959h1.051l2.073-1.961m-.567 2.82l3.622.684m-6.505 1.029l-.7 1.717");
}

.pcamfrbaw {
  d: path("m21.834 16.32l.548-2.95l-1.118-1.46l.627-1.563l4.293 1.33l5.814-4.03l3.446.695l1.534 2.312l-2.205 1.656l-1.072-1.277l-1.962-.43l-3.79 2.6l-2.125 5.396l1.597 2.32l-6.493 4.091l-5.91-2.575l-3.828 2.344l.041 2.252L9.7 28.184l-5.2-3.198l5.814-3.842l6.702-1.37l6.817-4.65l1.743-3.38");
}

.qsdgmbbbv {
  d: path("M24.61 32.875c0 4.13-3.35 7.478-7.482 7.478s-7.483-3.348-7.483-7.478s3.35-7.479 7.483-7.479s7.482 3.348 7.482 7.479");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
