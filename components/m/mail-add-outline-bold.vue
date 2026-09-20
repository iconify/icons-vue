<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="vizlgibdt"/><path class="im9sid5gw"/><path class="la-twzbff"/><path class="zpdz8rbaf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mail-add-outline-bold" /></template>
<style>
.im9sid5gw {
  d: path("m5 9.5 7 -7 7 7");
}

.la-twzbff {
  d: path("M12 12.5v6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.vizlgibdt {
  d: path("M3 11.5a2 2 0 0 1 2 -2h14a2 2 0 0 1 2 2V20a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.zpdz8rbaf {
  d: path("M9 15.5h6");
}

</style>
