<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="vl82kc5bq"/><path class="a_jn3kb_f"/><circle class="izughpqqk"/><circle class="xjqjd_b1j"/><circle class="n04k9ebyq"/><circle class="qx87bmbxr"/><circle class="wqfbbmbvn"/><circle class="b6-ylfqlk"/><circle class="vnq6jwbnp"/><circle class="x0ow6cbkq"/><circle class="t66ylq1cb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:last-quarter-moon" /></template>
<style>
.a_jn3kb_f {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M36 18c0 9.941-8.059 18-18 18V0c9.941 0 18 8.059 18 18");
}

.b6-ylfqlk {
  cx: 30px;
  cy: 9px;
  r: 1px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.izughpqqk {
  cx: 10.5px;
  cy: 8.5px;
  r: 3.5px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.n04k9ebyq {
  cx: 22.5px;
  cy: 27.5px;
  r: 3.5px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.qx87bmbxr {
  cx: 21px;
  cy: 6px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.t66ylq1cb {
  cx: 10px;
  cy: 23px;
  r: 2px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.vl82kc5bq {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M18 0v36C8.059 36 0 27.941 0 18S8.059 0 18 0");
}

.vnq6jwbnp {
  cx: 15px;
  cy: 31px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.wqfbbmbvn {
  cx: 3px;
  cy: 18px;
  r: 1px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

.x0ow6cbkq {
  cx: 32px;
  cy: 19px;
  r: 2px;
  fill: var(--svg-color--5b6876, #5b6876);
}

.xjqjd_b1j {
  cx: 24px;
  cy: 16px;
  r: 3px;
  fill: var(--svg-color--5b6876, #5b6876);
}

</style>
