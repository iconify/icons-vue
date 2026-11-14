<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="k90kj4z_r"/><path class="dt_wpxbdg"/><path class="sbezkcbzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:deposit-notice" /></template>
<style>
.dt_wpxbdg {
  d: path("M4.5 10.5h-2v3h2m3.25-2.75h.01M10.5 8.5h3m2 6.25h5m-5 6.5h5m-4-6.5v1l3 4.5v1");
}

.k90kj4z_r {
  d: path("M14 18.485v-.735c-.75.25-1.25.25-2 .25s-1.25 0-2-.25v1.75H7.5V17C5.25 16 4 14.25 4 12c0-3.5 3.5-6 8-6c4.461 0 7.939 2.457 7.999 5.909");
}

.sbezkcbzn {
  d: path("M19.5 14.75v1l-3 4.5v1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
