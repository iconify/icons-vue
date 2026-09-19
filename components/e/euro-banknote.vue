<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="d9asr-kih"/><path class="bs891acod"/><path class="c3l22j6pw"/><path class="wr133ibph"/><path class="t9sp_wbvn"/><circle class="cfz__9t6c"/><path class="g0169xokb"/><path class="jhbdihcde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:euro-banknote" /></template>
<style>
.bs891acod {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M0 8.5h64v38H0z");
}

.c3l22j6pw {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M24 46.5h16v9H24z");
}

.cfz__9t6c {
  cx: 45px;
  cy: 27.5px;
  r: 8px;
  fill: var(--svg-color--428bc1, #428bc1);
}

.d9asr-kih {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M0 46.5h64v9H0z");
}

.g0169xokb {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M24 8.5h16v38H24z");
}

.jhbdihcde {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.3 33.5c-2.2 0-4.2-1.2-5.2-3h6.7v-2h-7.4c-.1-.3-.1-.7-.1-1s0-.7.1-1h7.4v-2h-6.7c1.1-1.8 3-3 5.2-3c.4 0 .8 0 1.2.1l.5-2c-.5-.1-1.1-.2-1.7-.2c-3.4 0-6.4 2.1-7.6 5H9v2h2.2c0 .3-.1.7-.1 1s0 .7.1 1H9v2h2.7c1.2 2.9 4.2 5 7.6 5c.6 0 1.1-.1 1.7-.2l-.5-2c-.3.3-.8.3-1.2.3");
}

.t9sp_wbvn {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M7 15.5h50v24H7z");
}

.wr133ibph {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M4 12.5h56v30H4z");
}

</style>
