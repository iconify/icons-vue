<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="imhpp79qe"/><path class="ry16btbeg"/><path class="jte9ogj6j"/><path class="bvubfybsi"/><path class="v6_qfgb0t"/><g class="n1mjunbsu"><path class="bd2beqwnl"/><path class="oc3im_b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-comoros" /></template>
<style>
.bd2beqwnl {
  d: path("M3.926 18a5.52 5.52 0 0 1 4.295-5.38a5.5 5.5 0 0 0-1.227-.142a5.522 5.522 0 1 0 0 11.044c.422 0 .832-.052 1.227-.142A5.52 5.52 0 0 1 3.926 18");
}

.bvubfybsi {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 11.5h36V18H0z");
}

.imhpp79qe {
  fill: var(--svg-color--3a75c4, #3a75c4);
  d: path("M0 18v9a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-9z");
}

.jte9ogj6j {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M0 18h36v6.5H0z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.oc3im_b9b {
  d: path("m7.62 14.875l.601-.437l.601.437l-.23-.706l.601-.437H8.45l-.229-.707l-.23.707h-.743l.601.437zm0 2.635l.601-.437l.601.437l-.23-.707l.601-.436H8.45l-.229-.707l-.23.707h-.743l.601.436zm0 2.635l.601-.437l.601.437l-.23-.707l.601-.437H8.45l-.229-.706l-.23.706h-.743l.601.437zm.601 2.198l.601.436l-.23-.706l.601-.437H8.45l-.229-.706l-.23.706h-.743l.601.437l-.229.706z");
}

.ry16btbeg {
  fill: var(--svg-color--ffc61e, #ffc61e);
  d: path("M36 18V9a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4v9z");
}

.v6_qfgb0t {
  fill: var(--svg-color--3d8e33, #3d8e33);
  d: path("M1.351 6.004A4 4 0 0 0 0 9v18c0 1.193.522 2.264 1.351 2.997L17.5 18z");
}

</style>
