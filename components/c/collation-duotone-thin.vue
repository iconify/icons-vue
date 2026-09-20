<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pq8_vobtx"/><path class="tpht7obqo"/><path class="opdnrnbnq"/><path class="ahz9fzb-m"/><path class="vbkg5sb2n"/><path class="jtrmczbpr"/><path class="f-x5yl3mg"/><path class="blzwzs-bz"/><path class="gyi-tobvb"/><path class="ztr6a0gki"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:collation-duotone-thin" /></template>
<style>
.ahz9fzb-m {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M20 5v14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.blzwzs-bz {
  d: path("M2 18h8");
}

.f-x5yl3mg {
  d: path("M2 12h11");
}

.gyi-tobvb {
  d: path("M20 5v14");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jtrmczbpr {
  d: path("M2 6h14");
}

.opdnrnbnq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pq8_vobtx {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 6h14");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.tpht7obqo {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M2 12h11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vbkg5sb2n {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m17 16 3 3 2 -2");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ztr6a0gki {
  d: path("m17 16 3 3 2 -2");
}

</style>
