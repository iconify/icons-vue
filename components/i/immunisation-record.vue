<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zyfridgii"/><path class="fp5lq51nk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:immunisation-record" /></template>
<style>
.fp5lq51nk {
  d: path("m14.914 7.464l2.122 2.122l-4.95 4.95l-2.122-2.122Zm-3.889 6.011l-1.768 1.768m5.657-7.779l2.122 2.122");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zyfridgii {
  d: path("M4 2.5h15.5v19H4Zm3.5 0v19");
}

</style>
