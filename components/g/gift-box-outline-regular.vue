<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="em8xf33qp"/><path class="rw6ho_bav"/><path class="l2bljsbmn"/><path class="s7xlnnb_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gift-box-outline-regular" /></template>
<style>
.em8xf33qp {
  d: path("M4 9v11h16V9");
}

.l2bljsbmn {
  d: path("M12 9v11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.s7xlnnb_i {
  d: path("M12 9 8 5h4");
}

</style>
