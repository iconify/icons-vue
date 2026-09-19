<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="fo1_54amk"><path class="tubuiny7f"/><path class="nxv6bzbjd"/></g><g class="qvsxkcc5p"><path class="d5pw59y9b"/><path class="l2myklb8k"/><path class="hh3r1nbwh"/></g><g class="fo1_54amk"><path class="jas-5ccya"/><path class="vuxdptzcc"/></g><g class="qvsxkcc5p"><path class="vgi5f6bfd"/><path class="jflq-bcgy"/><path class="z4-ua0bxm"/></g><path class="tjpwdfxcz"/><g class="qvsxkcc5p"><path class="rou8qccts"/><path class="moyu_9bxc"/><path class="rdna0dbuy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:cactus" /></template>
<style>
.d5pw59y9b {
  d: path("M26.9 28.5v-1.2h-11c-.2 0-1.7-.1-1.7-1.8v-7c0-4.3-3-4.9-3-4.9s1.9.8 1.9 4.9v7.7c0 2.2 1.8 2.2 2.2 2.2z");
}

.fo1_54amk {
  fill: var(--svg-color--83bf4f, #83bf4f);
}

.hh3r1nbwh {
  d: path("M9.2 29.4V18.5c0-4.1 1.9-4.9 1.9-4.9s-3 .6-3 4.9V30c0 3.3 2.8 3.3 3.3 3.3H27v-1.2H12c-.3.1-2.8-.2-2.8-2.7");
}

.jas-5ccya {
  d: path("M46.4 47.2c0 2.1 1.8 3.9 3.9 3.9H53c2.2 0 3.9-1.7 3.9-3.9V30c0-7.6-10.6-7.6-10.6 0c.1 0 .1 17.2.1 17.2");
}

.jflq-bcgy {
  d: path("M48.7 45.1c.3 0 2.3-.3 2.3-3.6V30.6c0-4.3.8-6.3.8-6.3s.8 2 .8 6.3v11.8c0 4.2-2.3 4.2-2.9 4.2H31.2v-1.5z");
}

.l2myklb8k {
  d: path("M13.4 29.7c-.2 0-1.8-.2-1.8-2.8v-8.4c0-3.3-.6-4.9-.6-4.9s-.6 1.5-.6 4.9v9.1c0 3.3 1.8 3.3 2.2 3.3H27v-1.2z");
}

.moyu_9bxc {
  d: path("M32.3 64V11c0-6.8-1.2-10-1.2-10S30 4.2 30 11v53z");
}

.nxv6bzbjd {
  d: path("M23.4 26.3c1.7 0 3 1.3 3 3v2.1c0 1.7-1.4 3-3 3H10c-1.7 0-3-1.3-3-3v-2.1c0-1.7 1.4-3 3-3z");
}

.qvsxkcc5p {
  fill: var(--svg-color--699635, #699635);
}

.rdna0dbuy {
  d: path("M27.3 64V11c0-8.4 3.8-10 3.8-10s-6.2 1.3-6.2 10v53z");
}

.rou8qccts {
  d: path("M37.4 64V11c0-8.7-6.2-10-6.2-10S35 2.6 35 11v53z");
}

.tjpwdfxcz {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M39.5 64H22.8V10c0-12 16.7-12 16.7 0z");
}

.tubuiny7f {
  d: path("M15.2 31.4c0 1.7-1.4 3-3 3H10c-1.7 0-3-1.3-3-3V18.1c0-5.9 8.2-5.9 8.2 0z");
}

.vgi5f6bfd {
  d: path("M31.3 43.5V42h14.2c.3 0 2.3-.1 2.3-2.3v-9.1c0-5.5 3.9-6.3 3.9-6.3s-2.4 1-2.4 6.3v10c0 2.9-2.3 2.9-2.9 2.9z");
}

.vuxdptzcc {
  d: path("M35.8 40.6c-2.2 0-3.9 1.7-3.9 3.9v2.7c0 2.1 1.8 3.9 3.9 3.9h17.3c2.2 0 3.9-1.7 3.9-3.9v-2.7c0-2.1-1.8-3.9-3.9-3.9z");
}

.z4-ua0bxm {
  d: path("M54.1 44.6v-14c0-5.3-2.4-6.3-2.4-6.3s3.9.8 3.9 6.3v14.9c0 4.2-3.7 4.2-4.2 4.2H31.2v-1.5h19.4c.3 0 3.5-.4 3.5-3.6");
}

</style>
