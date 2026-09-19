<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="nv_n5pb_p"><circle class="pxxlxspmf"/><circle class="nqj9smbuw"/></g><path class="zp7y9t6gb"/><circle class="fo58ncc6s"/><path class="mk7aslbnp"/><circle class="c4poycc8u"/><path class="qwbw-gksc"/><circle class="oho_18b1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flushed-face" /></template>
<style>
.c4poycc8u {
  cx: 20.5px;
  cy: 29.1px;
  r: 4.5px;
  fill: var(--svg-color--664e27, #664e27);
}

.fo58ncc6s {
  cx: 32px;
  cy: 49.5px;
  r: 4.5px;
  fill: var(--svg-color--664e27, #664e27);
}

.mk7aslbnp {
  fill: var(--svg-color--fff, #fff);
  d: path("M29.5 29.1c0 5-4 9-9 9s-9-4-9-9s4-9 9-9s9 4.1 9 9");
}

.nqj9smbuw {
  cx: 11.2px;
  cy: 37.1px;
  r: 8px;
}

.nv_n5pb_p {
  fill: var(--svg-color--ff717f, #ff717f);
}

.oho_18b1r {
  cx: 43.5px;
  cy: 29.1px;
  r: 4.5px;
  fill: var(--svg-color--664e27, #664e27);
}

.pxxlxspmf {
  cx: 52.8px;
  cy: 37.1px;
  r: 8px;
}

.qwbw-gksc {
  fill: var(--svg-color--fff, #fff);
  d: path("M52.5 29.1c0 5-4 9-9 9s-9-4-9-9s4-9 9-9s9 4.1 9 9");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.zp7y9t6gb {
  fill: var(--svg-color--917524, #917524);
  d: path("M54.6 20.6c-2.7-3.3-6.7-5.1-11-5.1c-.6 0-.7-2.2 0-2.2c4.9 0 9.5 2.1 12.7 5.9c.5.6-1.3 1.9-1.7 1.4m-34.3-5.2c-4.2 0-8.3 1.9-11 5.1c-.4.5-2.1-.8-1.7-1.4c3.1-3.8 7.8-5.9 12.7-5.9c.7 0 .6 2.2 0 2.2");
}

</style>
