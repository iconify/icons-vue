<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lpx5u6brl"/><path class="rbluedc7v"/><path class="i66r_4qzk"/><path class="n_se78lku"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bitwise" /></template>
<style>
.i66r_4qzk {
  fill: currentColor;
  d: path("M13.426 13.402q-.14.142-.304.254q-.165.112-.349.189t-.379.116T12 14H7.5V9.5q0-.098.01-.196q.009-.098.028-.194q.02-.097.048-.191q.029-.094.066-.184q.038-.091.084-.178q.046-.086.101-.168t.117-.158t.132-.145t.145-.132q.076-.062.158-.117t.168-.101t.178-.084q.09-.037.184-.066q.094-.028.191-.048q.096-.019.194-.028T9.5 7.5H14V12q0 .264-.068.518");
}

.lpx5u6brl {
  d: path("M13.2 14H2.5V2.5H14v9.9");
}

.n_se78lku {
  d: path("m21 21.5l-4.75-5.25a1.75 1.75 0 1 1 2.5.25l-3 2a1.75 1.75 0 0 0 1 3h.75q2.25 0 3.5-3");
}

.rbluedc7v {
  d: path("M12.4 19H7.5V7.5H19v3.3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
