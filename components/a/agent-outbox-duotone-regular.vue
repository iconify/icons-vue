<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zjhvtnwqh"/><path class="xw3z49b3r"/><path class="a8z22qcqo"/><path class="y77rb0b0a"/><path class="rk0ztqbwb"/><path class="ag39tfb0x"/><path class="zy0mbfbon"/><path class="inae6abkl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:agent-outbox-duotone-regular" /></template>
<style>
.a8z22qcqo {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M17 8v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ag39tfb0x {
  d: path("M12 15v6h10v-6");
}

.inae6abkl {
  d: path("M14.5 10.5 17 8l2.5 2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rk0ztqbwb {
  d: path("M7.69 3.37a4 4 0 1 1 -3.38 0");
}

.xw3z49b3r {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 15v6h10v-6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y77rb0b0a {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M14.5 10.5 17 8l2.5 2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zjhvtnwqh {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M7.69 3.37a4 4 0 1 1 -3.38 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.zy0mbfbon {
  d: path("M17 8v5");
}

</style>
