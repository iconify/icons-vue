<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><g class="y9tr6bcfx"><path class="x_efjibbl"/><path class="be7ab7blk"/><path class="amglnac4x"/><path class="t7fsqqbzv"/><path class="s9gps-7br"/></g><circle class="ladi-rbfz"/><circle class="gficjdb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:kobold" /></template>
<style>
.amglnac4x {
  d: path("M38.941 23.693a43.3 43.3 0 0 0-3.22-11.927c-.192-2.427-.708-3.57-2.834-5.49c-1.32 1.858-1.995 4.27.193 6.112c-5.746-.159-15.424.69-19.566 4.226c-.369-2.607-1.686-4.025-3.618-4.758c-1.233 2.403-1.215 4.99 1.82 7.253c-1.43 2.7-1.09 5.904-.005 8.672m16.971 10.867c1.397-.22 2.605-1.91 3.852-3.523c1.192-1.544 2.629-3.448 3.84-5.312m-26.067-.403c1.642-.067 3.116.182 4.615.383m-3.982.648l2.557-.1m-2.317.925l2.048.96");
}

.be7ab7blk {
  d: path("M18.448 34.779c2.952 3.233 4.92 4.454 7.346 4.313M36.658 27.75c.827.25 1.654.389 2.48.322m-2.706-1.155c1.33.29 2.36.336 3.07.118m-2.087-.405l1.999-.61m-2.617.107l2.753-1.221M33.207 8.747c.456 1.173.583 1.771.725 2.79M10.27 13.669c.962 1.253 1.416 2.152 1.75 3.621");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.gficjdb8o {
  cx: 17.828px;
  cy: 21.642px;
  r: 0.75px;
  fill: currentColor;
}

.ladi-rbfz {
  cx: 29.709px;
  cy: 19.523px;
  r: 0.75px;
  fill: currentColor;
}

.s9gps-7br {
  d: path("M35.49 18.722c-.982-2.28-2.334-2.685-4.335-2.388c-2.675.397-5.024 1.052-6.41 3.766m-2.961 1.404c-1.217 4.778-7.548 4.411-8.941.963m-.233.002c1.94-4.393 6.807-4.384 9.19-3.203");
}

.t7fsqqbzv {
  d: path("M24.864 20c1.662 2.312 8.31 4.14 9.078.243");
}

.x_efjibbl {
  d: path("M10.628 32.644c-1.935 1.424-3.678 4.294-4.162 8.463m30.658-12.493c2.028 1.398 3.597 4.288 5.376 7.218m-13.839 3.001c0 .892-.433 1.384-1.325 1.384s-1.587-.611-1.587-1.503s.405-1.496 1.297-1.496s1.615.723 1.615 1.615");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
