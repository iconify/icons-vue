<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="oho4is9tg"/><path class="ab0x7ibdu"/><circle class="bu--3-bhs"/><circle class="i-gooi8ud"/><circle class="iy1p8v1tz"/><circle class="d3lgltbvk"/><circle class="j0p6cdzge"/><circle class="dd4w8hwwa"/><circle class="cdodtwbzn"/><circle class="o6wr86bln"/><circle class="y9st8ny3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:first-quarter-moon" /></template>
<style>
.ab0x7ibdu {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M0 18c0 9.941 8.059 18 18 18V0C8.059 0 0 8.059 0 18");
}

.bu--3-bhs {
  cx: 25.5px;
  cy: 8.5px;
  r: 3.5px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.cdodtwbzn {
  cx: 21px;
  cy: 31px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.d3lgltbvk {
  cx: 15px;
  cy: 6px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.dd4w8hwwa {
  cx: 6px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.i-gooi8ud {
  cx: 12px;
  cy: 16px;
  r: 3px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.iy1p8v1tz {
  cx: 13.5px;
  cy: 27.5px;
  r: 3.5px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.j0p6cdzge {
  cx: 33px;
  cy: 18px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.o6wr86bln {
  cx: 4px;
  cy: 19px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.oho4is9tg {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M18 0v36c9.941 0 18-8.059 18-18S27.941 0 18 0");
}

.y9st8ny3n {
  cx: 26px;
  cy: 23px;
  r: 2px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

</style>
