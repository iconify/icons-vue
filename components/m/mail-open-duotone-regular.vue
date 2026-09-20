<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="he5ikxbaq"/><path class="f_d2-rb8m"/><path class="az5fbcwwq"/><path class="ckawxab4i"/><path class="zr5lbkq8n"/><path class="ujkepejes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-open-duotone-regular" /></template>
<style>
.az5fbcwwq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6 12 6 6 6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ckawxab4i {
  d: path("m4 11 8 -8 8 8");
}

.f_d2-rb8m {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 11v10h16V11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.he5ikxbaq {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m4 11 8 -8 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ujkepejes {
  d: path("m6 12 6 6 6 -6");
}

.zr5lbkq8n {
  d: path("M4 11v10h16V11");
}

</style>
