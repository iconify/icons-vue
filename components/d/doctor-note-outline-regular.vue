<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="o2mxw0jtm"/><path class="qr1iqpomq"/><path class="j4po9lbmx"/><path class="g_cfe6uls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:doctor-note-outline-regular" /></template>
<style>
.g_cfe6uls {
  d: path("m10 16 3 -3 4 4");
}

.j4po9lbmx {
  d: path("M7 16h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2mxw0jtm {
  d: path("M12 5v6");
}

.qr1iqpomq {
  d: path("M9 8h6");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
