<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jnxnbxa0b"/><path class="x_7wq3p0y"/><path class="z_c7updjp"/><path class="xtgfndbtr"/><path class="hk70mwb8s"/><path class="ld5dubbqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fork-knife-outline-regular" /></template>
<style>
.hk70mwb8s {
  d: path("m16 4 3 3v6h-3Z");
}

.jnxnbxa0b {
  d: path("M5 3v5");
}

.ld5dubbqb {
  d: path("M17.5 13v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x_7wq3p0y {
  d: path("M9 3v5");
}

.xtgfndbtr {
  d: path("M7 8v13");
}

.z_c7updjp {
  d: path("M5 8h4");
}

</style>
