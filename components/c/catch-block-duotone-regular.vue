<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p7air0nan"/><path class="kqavb5qkt"/><path class="gwlxvvbgd"/><path class="f-52c6b3g"/><path class="rr985ibot"/><path class="v7xfanbfw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:catch-block-duotone-regular" /></template>
<style>
.f-52c6b3g {
  d: path("M4 10v10h16V10");
}

.gwlxvvbgd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 3v2.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.kqavb5qkt {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10v10h16V10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p7air0nan {
  fill: currentColor;
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rr985ibot {
  d: path("M12 3v2.5");
}

.v7xfanbfw {
  d: path("M11 8.5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

</style>
