<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="x6ei3vbab"/><path class="pga6n1bci"/><path class="d86s1p0qs"/><path class="srzgk7jml"/><path class="jkuojibnm"/><path class="eo60n2g2k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bell-off-duotone-regular" /></template>
<style>
.d86s1p0qs {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m6.5 6.5 10 10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.eo60n2g2k {
  d: path("m6.5 6.5 10 10");
}

.jkuojibnm {
  d: path("M3 20h18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pga6n1bci {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 20h18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.srzgk7jml {
  d: path("M3 17a9 9 0 0 1 18 0");
}

.x6ei3vbab {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M3 17a9 9 0 0 1 18 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
