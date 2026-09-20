<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rjb6iab1i"/><path class="xkw-kioym"/><path class="hd0bezdcu"/><path class="f7kl6pbji"/><path class="ftqzjnb8u"/><path class="u649he-6w"/><path class="f-x5yl3mg"/><path class="vsmfi0bcq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:intrusion-duotone-regular" /></template>
<style>
.f-x5yl3mg {
  d: path("M2 12h11");
}

.f7kl6pbji {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m10 9 3 3 -3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ftqzjnb8u {
  d: path("M6 3v18");
}

.hd0bezdcu {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rjb6iab1i {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M6 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.u649he-6w {
  d: path("M18 3v18");
}

.vsmfi0bcq {
  d: path("m10 9 3 3 -3 3");
}

.xkw-kioym {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
