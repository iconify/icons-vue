<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ifsz0izyq"/><path class="j-rdw_bvv"/><path class="t1rg4fbhf"/><path class="pf-zwj5ei"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:following-outline-regular" /></template>
<style>
.ifsz0izyq {
  d: path("M12 8a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.j-rdw_bvv {
  d: path("M11 17a4 4 0 0 1 8 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pf-zwj5ei {
  d: path("m6 10 2 2 -2 2");
}

.t1rg4fbhf {
  d: path("M3 12h5");
}

</style>
