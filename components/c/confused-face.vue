<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="bx8d1l6sr"/><g class="fbp0m0b1e"><circle class="eo72js8ki"/><circle class="eq5ew_blx"/><path class="fs5pg7byj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:confused-face" /></template>
<style>
.bx8d1l6sr {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("M2.5 37.2c2.9 16.3 18.4 27.2 34.8 24.3c16.3-2.9 27.2-18.4 24.3-34.8C58.7 10.5 43.1-.4 26.8 2.5C10.5 5.3-.4 20.9 2.5 37.2");
}

.eo72js8ki {
  cx: 42.4px;
  cy: 24.7px;
  r: 5px;
}

.eq5ew_blx {
  cx: 19.7px;
  cy: 28.7px;
  r: 5px;
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.fs5pg7byj {
  d: path("M43.3 41.8c-5.8-1.5-12-.4-16.9 3c-1.2.9 1.1 4 2.3 3.2c3.2-2.3 8.4-3.8 13.7-2.4c1.3.3 2.4-3.3.9-3.8");
}

</style>
