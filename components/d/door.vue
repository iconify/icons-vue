<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="z-uw70gel"/><path class="kgbdl-qcj"/><path class="u9vxl3iss"/><path class="i2f-tcj_g"/><path class="ptm69v8rq"/><path class="xx10kaczv"/><path class="n3_r1xlst"/><path class="vmglgnbrv"/><path class="lpj--ypas"/><circle class="dv7hb5b1n"/><path class="vgy2vpbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:door" /></template>
<style>
.dv7hb5b1n {
  cx: 51px;
  cy: 33px;
  r: 2.9px;
  fill: var(--svg-color--b78300, #b78300);
}

.i2f-tcj_g {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M0 61h64v3H0z");
}

.kgbdl-qcj {
  fill: var(--svg-color--594640, #594640);
  d: path("M7.2 31.2V61h49.5V31.2C56.8-5 7.2-4.5 7.2 31.2");
}

.lpj--ypas {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("m52 41.2l-.4-2.7c.2-.2.4-.5.4-.8c0-.6-.4-1-1-1s-1 .4-1 1c0 .3.2.6.4.8l-.4 2.7z");
}

.n3_r1xlst {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M47.5 28.9h7v14h-7z");
}

.ptm69v8rq {
  fill: var(--svg-color--594640, #594640);
  d: path("M35.2 30.5h16.6c-.6-12.1-8.3-18.6-16.6-19.8zm-5.5 0V10.8c-8.3 1.2-16 7.9-16.6 19.7zm5.5 5.6h16.7V56H35.2zm-22.2 0h16.7V56H13z");
}

.u9vxl3iss {
  fill: var(--svg-color--a37d64, #a37d64);
  d: path("M8 31.7V61h48V31.7c0-35.8-48-35.2-48 0");
}

.vgy2vpbch {
  fill: var(--svg-color--ffd664, #ffd664);
  d: path("M53.8 32.5c0 1.6-1.3 2.9-2.9 2.9S48 34.1 48 32.5s1.3-2.9 2.9-2.9s2.9 1.3 2.9 2.9");
}

.vmglgnbrv {
  fill: var(--svg-color--f2b200, #f2b200);
  d: path("M48 29.4h6v13h-6z");
}

.xx10kaczv {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M34.8 30.1h16.6c-.6-12.1-8.3-18.6-16.6-19.8zm-5.6 0V10.4c-8.3 1.2-16 7.9-16.6 19.7zm5.6 5.6h16.7v19.9H34.8zm-22.3 0h16.7v19.9H12.5z");
}

.z-uw70gel {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M3 29v32h58V29C61-10 3-9.4 3 29");
}

</style>
