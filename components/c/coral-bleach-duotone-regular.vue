<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="cepu0gbyk"/><path class="pueoa0wrv"/><path class="ic09aidxn"/><path class="fnbgpcbhf"/><path class="hi_p99g8p"/><path class="e61un8b5s"/><path class="bpe7e61mu"/><path class="w5v-kac9c"/><path class="og6hgh--o"/><path class="bos0j4biy"/><path class="xdkb5ybpc"/><path class="hhrer6blk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coral-bleach-duotone-regular" /></template>
<style>
.bos0j4biy {
  d: path("M3 21h18");
}

.bpe7e61mu {
  d: path("M8 21v-9L5 9");
}

.cepu0gbyk {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M8 21v-9L5 9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.e61un8b5s {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m21 4 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.fnbgpcbhf {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 21h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hhrer6blk {
  d: path("m21 4 -5 5");
}

.hi_p99g8p {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m16 4 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ic09aidxn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 21V11l-3 -3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.og6hgh--o {
  d: path("M15 21V11l-3 -3");
}

.pueoa0wrv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m8 15 4 -4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.w5v-kac9c {
  d: path("m8 15 4 -4");
}

.xdkb5ybpc {
  d: path("m16 4 5 5");
}

</style>
