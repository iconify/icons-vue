<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="rcj5jwbwh"/><path class="bo429ubsw"/><path class="btvzlsbgh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:book-contract" /></template>
<style>
.bo429ubsw {
  d: path("M12 2.5V8h5.5m-11 3H11m-4.5 6.5c1-2 2-2 2.5 0c.5 1.5 1.5 1 2-.5m3.5 3v-5a1.5 1.5 0 0 1 1.5-1.5h5.5v8H16a1.5 1.5 0 0 1-1.5-1.5Z");
}

.btvzlsbgh {
  d: path("M14.5 20a1.5 1.5 0 0 1 1.5-1.5h5.5");
}

.rcj5jwbwh {
  d: path("M17.5 10.685V8L12 2.5H5.5q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132q-.07.069-.132.145t-.117.158t-.101.168t-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T3.5 4.5v15q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028t.196.01h6.243");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
