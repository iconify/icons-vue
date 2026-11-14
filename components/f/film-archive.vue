<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mdyt89b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:film-archive" /></template>
<style>
.mdyt89b7v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3H19v4.5H2.5ZM4 7.5v9q0 .098.01.196q.009.098.028.194q.02.097.048.191q.029.094.066.184q.038.091.084.178q.046.086.101.168t.117.158t.132.145q.069.07.145.132t.158.117t.168.101q.087.046.178.084q.09.037.184.066q.094.028.191.048q.096.019.194.028T6 18.5h6.172m5.328-6.243V7.5m-9.25 4h5m1.75 7a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm3.5-1.5h.01m-1.26 2.25h.01m2.49 0h.01");
}

</style>
