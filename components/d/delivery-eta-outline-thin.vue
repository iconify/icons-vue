<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zzqmd5b6z"/><path class="kiksj5oln"/><path class="q7h9nybxu"/><path class="wrfjs43gu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:delivery-eta-outline-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kiksj5oln {
  d: path("M12 12a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.q7h9nybxu {
  d: path("M16 9v3");
}

.wrfjs43gu {
  d: path("M16 12h3");
}

.zzqmd5b6z {
  d: path("M8 4H3v16h5");
}

</style>
