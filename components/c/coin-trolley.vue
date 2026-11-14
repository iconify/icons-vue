<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="le4dfac5z"/><path class="xsqpe-5et"/><path class="k968t5q1o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:coin-trolley" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k968t5q1o {
  d: path("M16.25 17.75a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

.le4dfac5z {
  d: path("M15.79 11H7.587q-.143 0-.284-.023t-.277-.069q-.135-.046-.262-.113q-.126-.067-.24-.154t-.212-.191t-.177-.223t-.14-.249q-.059-.13-.097-.268l-.545-2q-.026-.097-.042-.196q-.015-.1-.018-.2q-.004-.101.004-.201t.027-.199t.05-.194q.03-.096.071-.188q.042-.092.093-.178q.052-.086.113-.166t.131-.153t.147-.136t.162-.118t.175-.1q.09-.044.184-.078q.095-.034.193-.057t.198-.034q.099-.012.2-.012h10.267q.098 0 .196.011q.097.011.193.033t.189.054q.092.033.181.075q.088.043.171.095t.16.114q.077.061.147.13q.069.07.13.147q.062.076.114.159q.052.084.095.172q.043.089.075.181q.033.093.054.189q.022.095.033.193t.012.196t-.011.196t-.033.193l-.454 2q-.038.165-.106.32q-.069.156-.166.295t-.219.256t-.265.21");
}

.xsqpe-5et {
  d: path("M2 3h2l2.75 11.5H10m-4.5 4.25h.01m3.99 0h.01m3.99-1a4.25 4.25 0 1 0 8.5 0a4.25 4.25 0 1 0-8.5 0");
}

</style>
