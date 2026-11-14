<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cx6ml40ig"/><path class="bf12zmbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cause-deafness" /></template>
<style>
.bf12zmbkf {
  d: path("M11.436 7.402q.393-.152.814-.152q.111 0 .221.011t.218.032q.108.022.214.054t.208.074q.102.043.2.095q.097.052.189.113t.177.132q.086.07.164.148t.148.164q.07.085.132.177q.061.092.113.189q.052.098.095.2q.042.102.074.208t.054.214t.032.218t.011.221c0 .32-.08.595-.206.844M3.5 3.5l17 17");
}

.cx6ml40ig {
  d: path("M8.583 4.571q.384-.318.817-.565t.901-.416t.96-.254t.989-.086q.141 0 .282.007t.282.021t.28.034t.278.048q.138.028.275.062q.137.035.272.076t.268.088t.263.102q.131.054.258.114q.128.06.253.127q.124.066.245.139t.239.151q.117.078.23.163q.114.084.223.173q.109.09.213.185q.105.094.205.194t.194.205q.095.104.185.213q.089.109.173.223q.085.113.163.23t.151.239t.139.245q.067.125.127.253q.06.127.114.258q.054.13.102.263t.088.268q.041.135.076.272t.062.275t.048.278t.034.28t.021.282T18 9c0 1.641-.66 2.733-1.36 3.687m-2.612 5.359q-.336.36-.753.621t-.887.406q-.255.078-.518.12q-.264.041-.53.045q-.267.004-.531-.03q-.265-.033-.522-.104t-.501-.178q-.244-.106-.471-.246t-.432-.311T8.5 18");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
