<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ff1tlbvvn"/><path class="j7xjeacfg"/><path class="lb2mnwy_k"/><path class="y6jfeezih"/><path class="sxv9iybuf"/><path class="tc7754bcs"/><path class="c5sgfbcqn"/><path class="l51-5cbmr"/><ellipse transform="rotate(-5.957 15.074 16.69)" class="ueo2_nbas"/><ellipse transform="rotate(-5.957 15.074 16.688)" class="s443ahbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:closed-mailbox-with-raised-flag" /></template>
<style>
.c5sgfbcqn {
  fill: var(--svg-color--52595e, #52595e);
  d: path("m19.6 16.4l-4.5 2.1l.3-3l3.2-1.5c1.2-.5 2.2 1.9 1 2.4");
}

.ff1tlbvvn {
  fill: var(--svg-color--b0bdc6, #b0bdc6);
  d: path("m38 64l-8.8-1.2v-49H38z");
}

.j7xjeacfg {
  fill: var(--svg-color--7d8b91, #7d8b91);
  d: path("M44.3 13.8H38V64l6.3-6.1z");
}

.l51-5cbmr {
  fill: var(--svg-color--333, #333);
  d: path("M18.4 16.1c.3 2.5-1.5 3.9-3 4c-.9.1-1.6-6.6-1.6-6.6s.9-.5 1.6-.5c1.5-.1 2.8 1.2 3 3.1");
}

.lb2mnwy_k {
  fill: var(--svg-color--333, #333);
  d: path("M46.8 0c-8.2 0-35.6 9.5-35.6 9.5l24.6 40.4l28.3-17V17C64 6.3 57.6 0 46.8 0");
}

.s443ahbyl {
  cx: 15.1px;
  cy: 16.7px;
  fill: var(--svg-color--697277, #697277);
  rx: 2.1px;
  ry: 2.6px;
}

.sxv9iybuf {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M37.2 6.4v29.2l2.8-1.3V15.6l11.2-4.3V1.6z");
}

.tc7754bcs {
  fill: var(--svg-color--333, #333);
  d: path("m9.7 22.8l2.6.3l-.1 10.7l-1.7-.2l.1-7.2v-1.8l-1.7 8.7l-1.7-.2l-1.5-9.2v1.8l-.1 7.2l-1.6-.2V22l2.6.3l1.5 8.6zm6.7.8l2 .3L21.3 35l-1.9-.3l-.5-2.3l-3.2-.4l-.6 2.1l-1.9-.3zm-.2 6.7l2.2.3l-1-4.3zm7.8 5.1l-1.8-.2l.1-10.7l1.8.2zm1.8-10.5l1.8.2l-.1 8.7l4.3.6v1.9l-6-.8z");
}

.ueo2_nbas {
  cx: 15.1px;
  cy: 16.7px;
  fill: var(--svg-color--52595e, #52595e);
  rx: 2.8px;
  ry: 3.5px;
}

.y6jfeezih {
  fill: var(--svg-color--697277, #697277);
  d: path("M17.2 8.5C6.4 8.5 0 16 0 26.8v17l35.7 6.1V29.2c0-10.8-7.6-20.7-18.5-20.7");
}

</style>
