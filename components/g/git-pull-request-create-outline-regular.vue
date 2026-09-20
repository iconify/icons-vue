<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kn0tcm93r"/><path class="k5nz3bcao"/><path class="fg8libqda"/><path class="pw61xnbei"/><path class="w7fxcjk_f"/><path class="l_raegbyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:git-pull-request-create-outline-regular" /></template>
<style>
.fg8libqda {
  d: path("M4 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.k5nz3bcao {
  d: path("M6 7.5v9");
}

.kn0tcm93r {
  d: path("M4 5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.l_raegbyq {
  d: path("M15.5 6.5h5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pw61xnbei {
  d: path("M16 19a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.w7fxcjk_f {
  d: path("M18 4v5");
}

</style>
