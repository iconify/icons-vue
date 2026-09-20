<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="qnvjj7b8l"/><path class="t7ftqibok"/><path class="tnh5d7byl"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="nb_catcjy"/><path class="jtt8g10_o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:add-checkpoint-duotone-regular" /></template>
<style>
.crv4i00bu {
  d: path("M4 3v18");
}

.jtt8g10_o {
  d: path("M9 10h6");
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.nb_catcjy {
  d: path("M12 7v6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qnvjj7b8l {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t7ftqibok {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 7v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tnh5d7byl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M9 10h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
