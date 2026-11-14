<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p7w_sob4f"/><path class="iu_segbmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-insurance-claim" /></template>
<style>
.iu_segbmd {
  d: path("M14.5 2.5v4h4m-4.805 6.25H7.25v-2l1.25-.5l1-1.75h2.75l1 1.75l1 .5v1.755m3.5 1.745l3.5 1.25V18c0 1.75-1.5 3-3.5 3.75c-2-.75-3.5-2-3.5-3.75v-2.5Z");
}

.p7w_sob4f {
  d: path("M18.5 11.585V6.5l-4-4h-8q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132q-.07.069-.132.145t-.117.158t-.101.168t-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T4.5 4.5V19q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T6.5 21h5.743");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
