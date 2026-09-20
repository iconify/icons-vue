<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x-yqofb9p"/><defs><path id="SVG3oexkd3A" class="ga5uvv7kl"/></defs><use href="#SVG3oexkd3A" class="dz-kf-l3n"/><clipPath id="SVGOJuBdbvO"><use href="#SVG3oexkd3A"/></clipPath><path clip-path="url(#SVGOJuBdbvO)" class="o3eit23hq"/><path class="l1hay9b5e"/><path class="rztqx_yqk"/><path class="ala4d-5-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:bus-stop" /></template>
<style>
.ala4d-5-h {
  fill: var(--svg-color--f79329, #f79329);
  d: path("M64 41.24c-11.34 0-20.57-9.23-20.57-20.57C43.43 9.32 52.66.09 64 .09s20.57 9.23 20.57 20.57c0 11.35-9.23 20.58-20.57 20.58m0-36.83c-8.96 0-16.26 7.29-16.26 16.26c0 8.96 7.29 16.26 16.26 16.26s16.26-7.3 16.26-16.26c0-8.97-7.29-16.26-16.26-16.26");
}

.dz-kf-l3n {
  fill: var(--svg-color--f79329, #f79329);
}

.ga5uvv7kl {
  d: path("M82.41 20.67c0 10.16-8.25 18.41-18.41 18.41s-18.41-8.25-18.41-18.41C45.59 10.5 53.84 2.25 64 2.25s18.41 8.24 18.41 18.42");
}

.l1hay9b5e {
  fill: var(--svg-color--fff, #fff);
  d: path("M47.03 46.9h33.41v52.54H47.03z");
}

.o3eit23hq {
  fill: var(--svg-color--fff, #fff);
  d: path("M41.86 16.26h43.66v10.51H41.86z");
}

.rztqx_yqk {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M80.44 102.14H47.03c-1.49 0-2.7-1.2-2.7-2.7V46.9c0-1.49 1.21-2.7 2.7-2.7h33.41c1.49 0 2.7 1.2 2.7 2.7v52.54c0 1.5-1.21 2.7-2.7 2.7m-30.72-5.39h28.02V49.6H49.72zm-5.17 31.16v-10.27c0-2.36 1.82-4.28 4.06-4.28h30.25c2.23 0 4.06 1.92 4.06 4.28v10.27z");
}

.x-yqofb9p {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M60.2 18.44h7.06v109.47H60.2z");
}

</style>
