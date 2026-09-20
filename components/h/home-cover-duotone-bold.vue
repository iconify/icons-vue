<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vspm3ybjo"/><path class="qcxa0jb0g"/><path class="vq3z6pogv"/><path class="olu_k327p"/><path class="a3eibhdgt"/><path class="z26gfvqcs"/><path class="dqv6w4kbm"/><path class="jkw9k9b1p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:home-cover-duotone-bold" /></template>
<style>
.a3eibhdgt {
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
}

.dqv6w4kbm {
  d: path("m8 16.5 4 -4 4 4");
}

.jkw9k9b1p {
  d: path("M9 16.5V21h6v-4.5");
}

.olu_k327p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 16.5V21h6v-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qcxa0jb0g {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vq3z6pogv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("m8 16.5 4 -4 4 4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vspm3ybjo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4.5 9.5a7.5 7.5 0 0 1 15 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z26gfvqcs {
  d: path("M4.5 9.5h15");
}

</style>
