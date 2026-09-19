<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zh86hvbqw"/><path class="a54l14beo"/><path class="aqx8tgb_h"/><circle class="ijpm7mfdr"/><circle class="j4ufd1vik"/><path class="co83z910z"/><path class="ff6q-9cab"/><circle class="c32y8elul"/><path class="crh5tnbap"/><g class="fo1_54amk"><ellipse class="b9ik5h8no"/><ellipse class="oemimbc2q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:frog-face" /></template>
<style>
.a54l14beo {
  fill: var(--svg-color--ffdf99, #ffdf99);
  d: path("M2 37.5c.3 4 6.6 21.6 30 21.5c23.3-.1 29.6-17.4 30-21.5c0 0-12.1 10-29.9 10c-18 0-30.1-10-30.1-10");
}

.aqx8tgb_h {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M26.3 32c-1.4 0-4.3 4-4.3 4s2.9-1.3 4.3-1.3s4.3 1.3 4.3 1.3s-2.9-4-4.3-4m11.4 0c-1.4 0-4.3 4-4.3 4s2.9-1.3 4.3-1.3S42 36 42 36s-2.9-4-4.3-4");
}

.b9ik5h8no {
  cx: 14px;
  cy: 11.6px;
  rx: 9.7px;
  ry: 5.4px;
}

.c32y8elul {
  cx: 14px;
  cy: 17px;
  r: 8px;
  fill: var(--svg-color--ffe655, #ffe655);
}

.co83z910z {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M54 17.2c0 2.2-1.8 4-4 4s-4-1.8-4-4s1.8-4 4-4s4 1.8 4 4");
}

.crh5tnbap {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M18 17.2c0 2.2-1.8 4-4 4s-4-1.8-4-4s1.8-4 4-4s4 1.8 4 4");
}

.ff6q-9cab {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M26 17c0 6.6-5.4 12-12 12S2 23.6 2 17S7.4 5 14 5s12 5.4 12 12");
}

.fo1_54amk {
  fill: var(--svg-color--83bf4f, #83bf4f);
}

.ijpm7mfdr {
  cx: 50px;
  cy: 17px;
  r: 12px;
  fill: var(--svg-color--83bf4f, #83bf4f);
}

.j4ufd1vik {
  cx: 50px;
  cy: 17px;
  r: 8px;
  fill: var(--svg-color--ffe655, #ffe655);
}

.oemimbc2q {
  cx: 50px;
  cy: 11.6px;
  rx: 9.7px;
  ry: 5.4px;
}

.zh86hvbqw {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M57.1 23.6C45.7 6.8 18.3 6.8 6.9 23.6c-4 5.9-5 12.5-4.9 13.9c.3 4 9.3 20.6 30 20.5c20.6-.1 29.6-16.4 30-20.5c.1-1.4-.9-8-4.9-13.9");
}

</style>
