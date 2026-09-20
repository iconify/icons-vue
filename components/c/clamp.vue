<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="z5-7j2buz"/><circle class="tpwvpwbog"/><path class="dqusv5boo"/><path class="q80a9aboh"/><path class="yt8ev4b4i"/><path class="dl106npch"/><path class="egxqilbsx"/><path class="uk55thb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:clamp" /></template>
<style>
.dl106npch {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M28 27a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2v-5a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2zm0-22a2 2 0 0 1-2 2h-7a2 2 0 0 1-2-2V4a2 2 0 0 1 2-2h7a2 2 0 0 1 2 2z");
}

.dqusv5boo {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M13 32h19v2H13z");
}

.egxqilbsx {
  fill: var(--svg-color--da2f47, #da2f47);
  d: path("M13 22a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h15V4a4 4 0 0 0-4-4H7a4 4 0 0 0-4 4v19a4 4 0 0 0 4 4h14a4 4 0 0 0 4-4v-1z");
}

.q80a9aboh {
  fill: var(--svg-color--9aaab4, #9aaab4);
  d: path("M20 15.502c0-1.381 1.119-1.5 2.5-1.5s2.5.119 2.5 1.5V33.5a2.5 2.5 0 1 1-5 0z");
}

.tpwvpwbog {
  cx: 32px;
  cy: 33px;
  r: 3px;
  fill: var(--svg-color--67757f, #67757f);
}

.uk55thb8r {
  fill: var(--svg-color--e75a70, #e75a70);
  d: path("M9 20a2 2 0 0 1-4 0V7a2 2 0 0 1 4 0z");
}

.yt8ev4b4i {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M27 15.002a2 2 0 0 1-2 2h-5a2 2 0 0 1-2-2c0-1.105.896-1 2-1h5c1.104 0 2-.104 2 1");
}

.z5-7j2buz {
  cx: 13px;
  cy: 33px;
  r: 3px;
  fill: var(--svg-color--67757f, #67757f);
}

</style>
