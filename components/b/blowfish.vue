<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dgha_v4qq"/><path class="wr76_4bht"/><path class="d41ki2bmu"/><ellipse class="x3-izh4nz"/><ellipse class="o6ilbmmdy"/><ellipse class="oeymhxnkk"/><ellipse class="f9a5utbiy"/><path class="ht06gh8zp"/><path class="u0_6g252i"/><path class="fuucr7dze"/><path class="vm6kb_bgq"/><g class="euxxm2bmm"><ellipse transform="rotate(-17.607 46.552 30.002)" class="o8x2-6bxv"/><ellipse transform="rotate(-17.598 46.557 23.48)" class="q2wngpb3r"/><ellipse transform="rotate(-17.591 44.036 25.084)" class="p44nf8bwm"/><ellipse transform="rotate(-59.17 15.184 17.042)" class="sc4msqbnc"/><path class="dfdbytbuw"/><ellipse transform="rotate(-59.163 17.763 13.823)" class="yoik7rblm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:blowfish" /></template>
<style>
.d41ki2bmu {
  fill: var(--svg-color--ffe2b3, #ffe2b3);
  d: path("m3.8 42.4l4.2-1c1.1 2.4 2.6 4.6 4.3 6.4L9 51.6l4.3-2.8c1.8 1.6 3.8 3 6 4L17 58.4l3.7-4.9c2 .8 4.2 1.3 6.4 1.5l-.3 7l2.1-7h.1c2 0 4-.3 5.8-.7l2.4 7.7l-.4-8.4q2.55-.9 4.8-2.4l5.4 7.2l-3.5-8.5c1.3-1 2.4-2.2 3.5-3.5l8 5.2l-6.6-7.2c.6-1 1.2-2.1 1.6-3.2c-8.5-2.7-18.7-4.3-28.4-4.3c-5.6 0-10.5.5-14.8 1.5c.2.7.4 1.4.7 2z");
}

.dfdbytbuw {
  d: path("M18.3 18.3c-.8-.5-.9-1.7-.2-2.8s1.8-1.6 2.6-1.2c.8.5.9 1.7.2 2.8c-.7 1.2-1.8 1.7-2.6 1.2");
}

.dgha_v4qq {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M9.1 47.7c-1.8 1.8-2.7 1-3.8-.1s-1.9-2-.1-3.8s5-4.2 6.1-3.1c1.1 1-.4 5.2-2.2 7");
}

.euxxm2bmm {
  fill: var(--svg-color--89664c, #89664c);
}

.f9a5utbiy {
  cx: 32px;
  cy: 26.7px;
  fill: var(--svg-color--29251c, #29251c);
  rx: 5.4px;
  ry: 5.6px;
}

.fuucr7dze {
  fill: var(--svg-color--29251c, #29251c);
  d: path("M17.5 38.7c.4-.7.8-1.4 1.3-1.9c.6-.6 1.3-1.1 2.1-1.3s1.7-.1 2.5.3c.7.4 1.3 1 1.7 1.7c-.6-.5-1.3-.9-2-1.1c-.7-.3-1.4-.3-2-.1c-.7.2-1.3.5-1.9 1c-.6.3-1.1.9-1.7 1.4");
}

.ht06gh8zp {
  fill: var(--svg-color--c1875d, #c1875d);
  d: path("M51.3 45.1c2.7 2.7 1.5 4.2-.1 5.9s-3.1 2.9-5.9.1c-2.7-2.7-6.5-7.7-4.8-9.4c1.6-1.6 8 .7 10.8 3.4");
}

.o6ilbmmdy {
  cx: 14.2px;
  cy: 26.7px;
  fill: var(--svg-color--29251c, #29251c);
  rx: 4.1px;
  ry: 4.2px;
}

.o8x2-6bxv {
  cx: 46.6px;
  cy: 30px;
  rx: 1.9px;
  ry: 2.7px;
}

.oeymhxnkk {
  cx: 32px;
  cy: 26.7px;
  fill: var(--svg-color--fcfcfa, #fcfcfa);
  rx: 7.8px;
  ry: 8.1px;
}

.p44nf8bwm {
  cx: 44px;
  cy: 25.1px;
  rx: 0.9px;
  ry: 1.2px;
}

.q2wngpb3r {
  cx: 46.6px;
  cy: 23.5px;
  rx: 1.4px;
  ry: 1.9px;
}

.sc4msqbnc {
  cx: 15.2px;
  cy: 17px;
  rx: 1.6px;
  ry: 1.1px;
}

.u0_6g252i {
  fill: var(--svg-color--ffe2b3, #ffe2b3);
  d: path("M12.6 37.4c5.2 0 5.1-2.6 8.3-3.3c2.6-.5 4.6 2.3 8.6 3.1");
}

.vm6kb_bgq {
  fill: var(--svg-color--e0bb86, #e0bb86);
  d: path("M18.3 39.5c-.2.1-.5.2-.7.2c-.3 0-.6 0-.8-.2c-.3-.2-.5-.4-.5-.7c-.1-.3 0-.5.1-.8c.1.2.2.5.3.7s.2.3.4.4c.2.2.7.3 1.2.4m7.9-2.8c.1.2.2.4.2.6s0 .5-.1.7s-.4.4-.6.4s-.5 0-.7-.1l.6-.3q.3-.15.3-.3c.1-.2.2-.6.3-1m-7.1 2.6c.3-.3.5-.7.9-.9q.45-.45 1.2-.6c.4-.1.9-.1 1.3.1s.7.5 1 .8c-.4-.2-.7-.4-1.1-.5s-.7-.1-1.1 0s-.7.2-1.1.4c-.4.3-.7.5-1.1.7");
}

.wr76_4bht {
  fill: var(--svg-color--c1875d, #c1875d);
  d: path("M50.1 41.2c.1-.3.3-.6.4-1l9.7 2.2l-8.9-4.7c.4-1.4.6-2.9.7-4.4L62 32l-10-1.3c-.1-1.5-.3-3-.7-4.4l8.9-4.7l-9.7 2.2c-.6-1.5-1.3-2.8-2.1-4.1l6.6-7.2l-8 5.2c-1-1.3-2.2-2.5-3.5-3.5L47 5.6l-5.4 7.2q-2.25-1.5-4.8-2.4l.4-8.4l-2.4 7.7C33 9.3 31 9 29 9h-.1l-2.1-7l.3 7.1c-2.2.2-4.4.7-6.4 1.5l-3.7-5l2.3 5.5c-2.2 1-4.2 2.4-6 4L9 12.4l3.4 3.7c-1.8 1.9-3.3 4-4.3 6.4l-4.2-1l3.8 2c-1 2.5-1.5 5.1-1.6 7.9L2 32l4 .5c0 2 .4 4 .9 5.9c4.2-1 9.2-1.5 14.8-1.5c9.7 0 19.9 1.6 28.4 4.3");
}

.x3-izh4nz {
  cx: 14.2px;
  cy: 26.7px;
  fill: var(--svg-color--fcfcfa, #fcfcfa);
  rx: 6px;
  ry: 6.2px;
}

.yoik7rblm {
  cx: 17.8px;
  cy: 13.8px;
  rx: 1px;
  ry: 0.7px;
}

</style>
