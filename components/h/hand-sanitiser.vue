<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="g247gfl5i"/><path class="xeipszbqe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hand-sanitiser" /></template>
<style>
.g247gfl5i {
  d: path("M6.5 10h11v11h-11Zm3.5 0V7.5h4V10m-2-2.5V4h5v1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xeipszbqe {
  d: path("M12 12.75s-2.25 2.5-2.25 3.75a2.25 2.25 0 0 0 4.5 0c0-1.25-2.25-3.75-2.25-3.75Z");
}

</style>
