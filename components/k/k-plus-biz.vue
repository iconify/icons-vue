<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q94nobbwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:k-plus-biz" /></template>
<style>
.q94nobbwc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 26.302V42m6.188-15.698H40.86L30.188 42H40.86m-27.074-7.849c2.224 0 4.027 1.757 4.027 3.925S16.01 42 13.786 42H7.14V26.302h6.645c2.224 0 4.027 1.757 4.027 3.925s-1.803 3.924-4.027 3.924Zm0 0H7.14m0-27.995h3.818v15.351H7.14zm7.758 4.841l8.293 10.709H20.12c-1.273 0-1.928-.828-2.602-1.707l-4.82-6.28zl2.619-3.29C18.19 6.827 18.847 6 20.119 6h3.072l-6.054 7.888m13.459-1.322v8.868M26.098 17h8.997");
}

</style>
