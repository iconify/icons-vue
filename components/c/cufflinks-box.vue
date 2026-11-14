<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t3j5alezd"/><path class="ykkwevnss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cufflinks-box" /></template>
<style>
.t3j5alezd {
  d: path("M3.549 8.254L4.5 3.5h15l.951 4.757M3 12.7v5.8q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145t.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T5 20.5h14q.098 0 .196-.01q.098-.009.194-.028q.097-.02.191-.048q.094-.029.184-.066q.091-.038.178-.084q.086-.046.168-.101t.158-.117t.145-.132t.132-.145t.117-.158t.101-.168q.046-.087.084-.178q.037-.09.066-.184q.028-.094.048-.191q.019-.096.028-.194T21 18.5v-5.843");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ykkwevnss {
  d: path("M5.5 11a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Zm8.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

</style>
