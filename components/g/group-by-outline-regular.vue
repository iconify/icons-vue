<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ybh1xwgpp"/><path class="qfe94rk-q"/><path class="ygvoi9umd"/><path class="hxoe7gx5p"/><path class="vox58lg-w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:group-by-outline-regular" /></template>
<style>
.hxoe7gx5p {
  d: path("M12 5v12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qfe94rk-q {
  d: path("M2 11h8");
}

.vox58lg-w {
  d: path("M12 11h10");
}

.ybh1xwgpp {
  d: path("M2 5h8");
}

.ygvoi9umd {
  d: path("M2 17h8");
}

</style>
