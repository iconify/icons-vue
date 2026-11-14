<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wq4i0gxlv"/><path class="nynzlpb7q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:data-archive" /></template>
<style>
.nynzlpb7q {
  d: path("M14.75 15.25v5c0 .75 1.5 1.25 3.25 1.25s3.25-.5 3.25-1.25v-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wq4i0gxlv {
  d: path("M2.5 3h19v5h-19ZM4 8v11q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T6 21h5.972M20 11.357V8M9.5 11.5h5m.25 3.75a3.25 1.25 0 1 0 6.5 0a3.25 1.25 0 1 0-6.5 0Z");
}

</style>
