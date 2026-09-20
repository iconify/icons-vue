<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="earylblsr"/><path class="fkiv9lbcn"/><path class="ynpftdv3e"/><path class="mzuepvbdd"/><path class="esrr3ybeu"/><path class="h427ybdsb"/><path class="y-08x0b7u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lcd" /></template>
<style>
.earylblsr {
  fill: var(--svg-color--4747f3, #4747f3);
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.esrr3ybeu {
  fill: var(--svg-color--e0e0fc, #e0e0fc);
  d: path("M12 19.333a7.332 7.332 0 1 0 0-14.665a7.332 7.332 0 0 0 0 14.665");
}

.fkiv9lbcn {
  fill: var(--svg-color--7c7cf4, #7c7cf4);
  d: path("M12 20.66a8.661 8.661 0 1 0 0-17.322a8.661 8.661 0 0 0 0 17.322");
}

.ft5dv1b6b {
  fill: none;
}

.h427ybdsb {
  fill: var(--svg-color--f0f3fa, #f0f3fa);
  d: path("M12 18.507a6.507 6.507 0 1 0 0-13.013a6.507 6.507 0 0 0 0 13.013");
}

.mzuepvbdd {
  fill: var(--svg-color--c4c5fb, #c4c5fb);
  d: path("M12 19.845a7.846 7.846 0 1 0 0-15.692a7.846 7.846 0 0 0 0 15.692");
}

.y-08x0b7u {
  fill: var(--svg-color--2a28f5, #2a28f5);
  d: path("M9.353 12.122v3.584h5.294v-1.588H11.47v-1.403a10 10 0 0 1-2.117-.593m0-1.446a21 21 0 0 0 2.117.678v-3.59H9.353z");
}

.ynpftdv3e {
  fill: var(--svg-color--a2a2f8, #a2a2f8);
  d: path("M12 20.284a8.285 8.285 0 1 0 0-16.57a8.285 8.285 0 0 0 0 16.57");
}

</style>
