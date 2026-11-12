<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="lxnzn9nmw"/><path class="vzy5f4b4h"/><path class="f6nccb4ip"/><path class="grep09bwo"/><path class="l3ir29pqm"/><path class="sy4dadcnw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:augmented-reality-line-duotone" /></template>
<style>
.f6nccb4ip {
  d: path("M6.875 13.2002H10.125");
}

.grep09bwo {
  stroke-linejoin: round;
  d: path("M14 8H16C17.1046 8 18 8.89543 18 10C18 11.1046 17.1046 12 16 12H15.5H14V8Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3ir29pqm {
  d: path("M14 16V12V8");
}

.lxnzn9nmw {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.sy4dadcnw {
  d: path("M15.5 12L18 16");
}

.vzy5f4b4h {
  stroke-linejoin: round;
  d: path("M6 16L8.5 8L11 16");
}

</style>
