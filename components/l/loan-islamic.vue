<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obycfcz1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:loan-islamic" /></template>
<style>
.obycfcz1g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 17L14.5 3m-11 1.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm10.108 9.095Q13.312 13.5 13 13.5q-.098 0-.196.01q-.098.009-.194.028q-.097.02-.191.048q-.094.029-.184.066q-.091.038-.178.084q-.086.046-.168.101t-.158.117t-.145.132t-.132.145t-.117.158t-.101.168q-.046.087-.084.178q-.037.09-.066.184q-.028.094-.048.191q-.019.096-.028.194T11 15.5q0 .195.038.386q.037.191.111.372q.074.18.181.343q.107.162.244.301M2.5 7.5l12.303 5.053M19.5 15.25a3.25 3.25 0 1 0 0 5.5a3 3 0 0 1 0-5.5Z");
}

</style>
