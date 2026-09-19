<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="csxqr7bvk"><path class="nc3k5fbas"/><path class="k_pn_9bsn"/><path class="etsg7mxek"/><path class="ss1siebod"/><path class="vnv82cbyd"/><path class="byl1r8w9f"/><path class="wblc5qbgo"/></g><g class="qwwgj218a"><path class="bd6ysib1k"/><path class="lf-lw8bih"/><path class="lx0vy8b8l"/><path class="wvx-cedgf"/></g><path class="xmu86hbpo"/><path class="bmoppuava"/><path class="qtvczx7jm"/><path class="uhsrq-bdb"/><g class="j9kx44b1g"><path class="z9pmv4evx"/><path class="i-8t-1j-r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:baby-chick" /></template>
<style>
.bd6ysib1k {
  d: path("M60.9 30.5c4.6 0-4.9 21.1-27.8 21.1c-15.6 0-26.5-6.6-26.5-18.8s8.6-24 24.2-20c15.9 4 4.7 17.7 30.1 17.7");
}

.bmoppuava {
  fill: var(--svg-color--e08828, #e08828);
  d: path("m3.4 31.2l5.6-1c0 2.6-.2 4.3-2.1 4.3c-1.8.1-3.5-.7-3.5-3.3");
}

.byl1r8w9f {
  d: path("M9.7 52.8c.3-.4 2.4-.2 4.1 1c1.8 1.2 2.6 3.1 2.3 3.5s-1.7-.7-3.5-1.9c-1.7-1.3-3.2-2.2-2.9-2.6");
}

.csxqr7bvk {
  fill: var(--svg-color--e08828, #e08828);
}

.etsg7mxek {
  d: path("M31.5 61.6c0-.5 1.8-1.5 4-1.5s4 1 4 1.5s-1.8.4-4 .4s-4 .1-4-.4");
}

.i-8t-1j-r {
  d: path("M51.2 36.9c-1.4.4-2.5-.2-2.5-.2c1.5-1.3 1.9-3.5 1.9-3.5c-1 .9-2.8.9-2.8.9c.5-1.6.2-2.8.2-2.8c-2.3 3.4-10.4 3.5-10.4 3.5c4.9 3.2 7.5 7.5 7.5 7.5c3.9-1.4 6.1-5.4 6.1-5.4");
}

.j9kx44b1g {
  fill: var(--svg-color--ffbf3e, #ffbf3e);
}

.k_pn_9bsn {
  d: path("M36.3 61.6c0-.5 1.8-1.5 4-1.5s4 1 4 1.5s-1.8.4-4 .4s-4 .1-4-.4");
}

.lf-lw8bih {
  d: path("M20 21.8c-1.1 4.3 12.4.2 9.9-8.6S19.1 2 19.1 2s3.8 8.5.9 19.8");
}

.lx0vy8b8l {
  d: path("M20.3 22.3c3.3 3.2 8-8.4-1.7-11.8S4.2 9.6 4.2 9.6s7.4 4.2 16.1 12.7");
}

.nc3k5fbas {
  d: path("M34.3 50.7h2.5v10.8h-2.5z");
}

.qtvczx7jm {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("m9 30.3l-7 1.9c0-3.2 2.6-6.8 4.9-6.8c2.4.1 2.1 1.7 2.1 4.9");
}

.qwwgj218a {
  fill: var(--svg-color--ffd93b, #ffd93b);
}

.ss1siebod {
  d: path("M26.8 61.6c0-.5 1.8-1.5 4-1.5s4 1 4 1.5s-1.8.4-4 .4s-4 .1-4-.4M14 55.7l-2-1.4l6.3-8.2l2 1.4z");
}

.uhsrq-bdb {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M11 25.1c0-1.6 1.3-3.3 2.9-3.3s2.9 1.7 2.9 3.3s-1.3 2.3-2.9 2.3c-1.6-.1-2.9-.8-2.9-2.3");
}

.vnv82cbyd {
  d: path("M13.5 55.4c.3-.4 2.4-.2 4.1 1c1.8 1.2 2.6 3.1 2.3 3.5s-1.7-.7-3.5-1.9c-1.7-1.2-3.2-2.2-2.9-2.6");
}

.wblc5qbgo {
  d: path("M6 50.1c.3-.4 2.4-.2 4.1 1c1.8 1.2 2.6 3.1 2.3 3.5s-1.7-.7-3.5-1.9s-3.3-2.2-2.9-2.6");
}

.wvx-cedgf {
  d: path("M31.3 25.7c-.3 4.3-12.1-2-6.9-10.1s14.1-8.9 14.1-8.9s-6.3 7.4-7.2 19");
}

.xmu86hbpo {
  fill: var(--svg-color--ffea92, #ffea92);
  d: path("M57.2 41.2c-5 .9-13.5 4.3-23 4.3c-11.4 0-21.2-4.8-25.5-4.5c3.8 6.9 12.8 10.6 24.4 10.6c11.4 0 19.4-5.2 24.1-10.4");
}

.z9pmv4evx {
  d: path("M48.5 37.3c0 5.3-6.7 9.6-15 9.6s-9.8-4.3-9.8-9.6s1.5-9.6 9.8-9.6s15 4.3 15 9.6");
}

</style>
