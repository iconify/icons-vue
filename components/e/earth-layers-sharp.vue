<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="irkzavb_i"/><path class="iuoqpbhrk"/><path class="w2okrhb6v"/><path class="lsjhyubrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earth-layers-sharp" /></template>
<style>
.irkzavb_i {
  d: path("M12 12V2.75A9.25 9.25 0 1 0 21.25 12Z");
}

.iuoqpbhrk {
  d: path("m6.5 8.75l1.818-.727l.432 1.727c.25 1-.25 1.5.5 2.25l1.417 1.417l-.417.833l-.917 1.833L7.75 14.5c-.75-.75-.6-1.6-1.4-2.2l-.953-.715l.253-1.435l.163-1.056zm5.5-6A9.25 9.25 0 0 1 21.25 12");
}

.lsjhyubrs {
  d: path("M12 12V9h3v3Z");
}

.w2okrhb6v {
  d: path("M12 6a6 6 0 0 1 6 6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
