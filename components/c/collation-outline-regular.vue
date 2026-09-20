<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="jtrmczbpr"/><path class="f-x5yl3mg"/><path class="blzwzs-bz"/><path class="gyi-tobvb"/><path class="ztr6a0gki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collation-outline-regular" /></template>
<style>
.blzwzs-bz {
  d: path("M2 18h8");
}

.f-x5yl3mg {
  d: path("M2 12h11");
}

.gyi-tobvb {
  d: path("M20 5v14");
}

.jtrmczbpr {
  d: path("M2 6h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ztr6a0gki {
  d: path("m17 16 3 3 2 -2");
}

</style>
