<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="pde7v9p3k"/><path class="mletw-bxm"/><path class="fonvfnbth"/><path class="x1opppb3l"/><g class="jeunsn1yj"><path class="t_5m7rbvx"/><path class="pcpbrbcdq"/></g><path class="qwv8mobvv"/><path class="ak872swvm"/><path class="i-1qa41pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:derelict-house" /></template>
<style>
.ak872swvm {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M40.2 3v2.1H38L44.5 9h3.2l4.3 2l-3.2-4H45zm.8 51h-9.8L29 47l2.2-7H41l-1.2 5.8z");
}

.fonvfnbth {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M63 14.4L38 0H26l24 18h12c.7 0 1.4-.3 1.7-1c.6-.9.3-2-.7-2.6");
}

.i-1qa41pz {
  fill: var(--svg-color--dbb471, #dbb471);
  d: path("M11.2 56L10 53.3L24.8 50l1.2 2.7zm14.3-7L10 46.1l.5-3.1L26 45.9z");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.mletw-bxm {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M50 16L26 4L6 24l3 8l-4 28h44l-4-13z");
}

.pcpbrbcdq {
  d: path("m55 39l-4 13.1l2.1 2.9zm-41.3 1H24l-2 11l2 9H13.7L12 47zm42-8H51l1.3-8H57zM24 32h-8l-2-8h8zm6 0h8l2-8h-8z");
}

.pde7v9p3k {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M0 60h64v4H0zm44-45v45h17l-4-23l4-22z");
}

.qwv8mobvv {
  fill: var(--svg-color--dbb471, #dbb471);
  d: path("m42 36l-4-4l2-8l4 4z");
}

.t_5m7rbvx {
  d: path("m49 44l3.4 16H57z");
}

.x1opppb3l {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M51 14.4L26 0L1 26.4C0 27-.3 28.1.3 29c.5 1 1.7 1.3 2.6.7L26 4l23.1 13.7c.9.5 2.1.2 2.6-.7c.6-.9.3-2-.7-2.6");
}

</style>
