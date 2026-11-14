<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e16rw79zh"/><path class="jfrm4etij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blog-post-plus" /></template>
<style>
.e16rw79zh {
  d: path("M19 12.185V8l-5.5-5.5H7q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132q-.07.069-.132.145t-.117.158t-.101.168t-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T5 4.5v15q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T7 21.5h8.243");
}

.jfrm4etij {
  d: path("M13.5 2.5V8H19M8.5 12h7m-7 4H12m6-1v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
