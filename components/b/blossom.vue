<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="skdfuq5ti"/><path class="sswuznbdl"/><path class="q11xc1a-x"/><path class="vp4_ucymb"/><circle class="pe3s_cb8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:blossom" /></template>
<style>
.pe3s_cb8y {
  cx: 32px;
  cy: 28px;
  r: 9.6px;
  fill: var(--svg-color--f29a2e, #f29a2e);
}

.q11xc1a-x {
  fill: var(--svg-color--ffd68d, #ffd68d);
  d: path("M50.3 19.6c-4.9 4.9-15 8.4-16.7 6.8c-1.6-1.6 1.8-11.8 6.8-16.7c6.9-6.9 16.8 3 9.9 9.9M13.7 36.4c4.9-4.9 15-8.4 16.7-6.8c1.6 1.6-1.9 11.7-6.8 16.7c-6.9 6.9-16.8-3-9.9-9.9m26.7 9.9c-4.9-4.9-8.4-15-6.8-16.7c1.6-1.6 11.8 1.8 16.7 6.8c6.9 6.9-3 16.8-9.9 9.9M23.6 9.7c4.9 4.9 8.4 15 6.8 16.7c-1.6 1.6-11.8-1.9-16.7-6.8c-6.9-6.9 3-16.8 9.9-9.9");
}

.skdfuq5ti {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M43.8 63.4c-7.7 2-11-2-11-2s.6-6.2 8.4-8.2c5.3-1.4 15.3 1.4 15.3 1.4s-7.4 7.4-12.7 8.8M21 58c7.7 2 11-2 11-2s-.6-6.2-8.4-8.2c-5.3-1.4-15.3 1.4-15.3 1.4S15.7 56.6 21 58");
}

.sswuznbdl {
  fill: none;
  stroke: var(--svg-color--75a843, #75a843);
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--4px, 4px);
  d: path("M32 28v36");
}

.vp4_ucymb {
  fill: var(--svg-color--ffe9ab, #ffe9ab);
  d: path("M50.9 35c-7 0-16.6-4.7-16.6-7s9.6-7 16.6-7c9.8 0 9.8 14 0 14M13.1 21c7 0 16.6 4.7 16.6 7s-9.6 7-16.6 7c-9.8 0-9.8-14 0-14M25 46.9c0-7 4.7-16.6 7-16.6s7 9.6 7 16.6c0 9.8-14 9.8-14 0M39 9.1c0 7-4.7 16.6-7 16.6s-7-9.6-7-16.6c0-9.8 14-9.8 14 0");
}

</style>
