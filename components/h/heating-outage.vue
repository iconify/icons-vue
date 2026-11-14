<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iv5394bci"/><path class="bukr1_b4e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heating-outage" /></template>
<style>
.bukr1_b4e {
  d: path("M8.5 18.5h7c1.5-2.5.5-6-2.5-10c0 3-1.5 4-2.5 2.5c-2.5 2.5-3 5.5-2 7.5Z");
}

.iv5394bci {
  d: path("M14.009 5.258L20 10.5v9q0 .098-.01.196q-.009.098-.028.194q-.02.097-.048.191q-.029.094-.066.184q-.038.091-.084.178q-.046.086-.101.168t-.117.158t-.132.145t-.145.132t-.158.117t-.168.101q-.087.046-.178.084q-.09.037-.184.066q-.094.028-.191.048q-.096.019-.194.028T18 21.5H6q-.098 0-.196-.01q-.098-.009-.194-.028q-.097-.02-.191-.048q-.094-.029-.184-.066q-.091-.038-.178-.084q-.086-.046-.168-.101t-.158-.117t-.145-.132q-.07-.069-.132-.145t-.117-.158t-.101-.168t-.084-.178q-.037-.09-.066-.184q-.028-.094-.048-.191q-.019-.096-.028-.194T4 19.5v-9l6.246-5.466M3 3l5.798 5.798m9.758 9.758L21 21m0-18l-4.95 4.95M5.514 18.486L3 21");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
