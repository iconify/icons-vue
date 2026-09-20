<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="k1z9arb3s"/><path class="kehh6il4b"/><path class="xxwpb5jry"/><path class="qpyqcm49x"/><path class="vpkze1zjp"/><circle class="z6tgjpb1z"/><circle class="zlbozpdwu"/><circle class="c4u9utwaj"/><path class="e--imabyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:balance-scale" /></template>
<style>
.c4u9utwaj {
  cx: 28px;
  cy: 10px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.e--imabyt {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M28 10c0 1.104 0 0-10 0S8 11.104 8 10s3-4 10-4s10 2.896 10 4");
}

.k1z9arb3s {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M3.923 22.923a1 1 0 1 1-1.847-.769L6.693 9.616a1 1 0 1 1 1.846.769z");
}

.kehh6il4b {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M13.923 22.154a1 1 0 0 1-1.847.769L7.461 10.385a1 1 0 0 1 1.847-.769zm10.001.769a1.001 1.001 0 0 1-1.847-.769l4.616-12.539a1 1 0 0 1 1.846.77z");
}

.qpyqcm49x {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M14.857 22H1.143C.512 22 0 22.511 0 23.143c0 2.524 3.582 4.571 8 4.571s8-2.047 8-4.571c0-.632-.512-1.143-1.143-1.143M24 34H12a1 1 0 0 1-1-1c0-2.209 3.134-4 7-4s7 1.791 7 4a1 1 0 0 1-1 1m10.857-12H21.143c-.632 0-1.143.511-1.143 1.143c0 2.524 3.581 4.571 8 4.571s8-2.047 8-4.571c0-.632-.511-1.143-1.143-1.143");
}

.vpkze1zjp {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M19 3a1 1 0 1 0-2 0v27a1 1 0 1 0 2 0z");
}

.xxwpb5jry {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M33.923 22.154a1 1 0 1 1-1.847.769l-4.615-12.538a1 1 0 1 1 1.846-.769z");
}

.z6tgjpb1z {
  cx: 18px;
  cy: 4px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

.zlbozpdwu {
  cx: 8px;
  cy: 10px;
  r: 2px;
  fill: var(--svg-color--ffac33, #ffac33);
}

</style>
