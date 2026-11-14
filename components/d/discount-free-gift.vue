<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cf72wo-mb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:discount-free-gift" /></template>
<style>
.cf72wo-mb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 8.5h9.5a1.75 1.75 0 0 1 1.75 1.75v.5a1.75 1.75 0 0 1-1.75 1.75h-9.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 4.25 8.5m-.75 4V19q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T5.5 21h7q.176 0 .349-.031q.173-.03.339-.091q.165-.06.317-.149q.152-.088.286-.202m.709-5.27V12.5M9 8.5c-3.5 0-4.5-5-2-5c1.5 0 2 2.5 2 5m0 0c3.5 0 4.5-5 2-5c-1.5 0-2 2.5-2 5m0 0V21m9-6v6m-3-3h6");
}

</style>
