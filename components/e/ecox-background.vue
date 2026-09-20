<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e2-21db_c"/><path clip-rule="evenodd" class="mq-u_wbgn"/><path class="t1reh5bmx"/><path class="kuc--qb_m"/><path class="vi5-a9b2c"/><path class="cm63n7u7p"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ecox-background" /></template>
<style>
.cm63n7u7p {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.673 5.881c.122.377.188.772.188 1.177c0 2.376-2.179 4.296-4.861 4.296s-4.861-1.92-4.861-4.296c0-.358.047-.706.14-1.035c-.512.329-.983.72-1.397 1.148C5.948 10.107 8.66 12.47 12 12.47c3.379 0 6.117-2.424 6.117-5.412v-.066a8 8 0 0 0-1.444-1.11");
}

.e2-21db_c {
  fill: var(--svg-color--021540, #021540);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.kuc--qb_m {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.589 7.718a4.673 4.673 0 0 0-5.85 4.527a4.674 4.674 0 0 0 5.337 4.636a7.6 7.6 0 0 1-1.247 1.237a5.88 5.88 0 0 1-5.3-5.868a5.883 5.883 0 0 1 5.954-5.897q.63.623 1.106 1.365");
}

.mq-u_wbgn {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 18.588c3.736 0 6.588-2.852 6.588-6.588S15.736 5.412 12 5.412S5.412 8.264 5.412 12S8.264 18.588 12 18.588M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t1reh5bmx {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.172 18.118a5.96 5.96 0 0 0 5.298-5.859c0-3.233-2.658-5.859-5.953-5.906c-.418.4-.785.843-1.105 1.318a5 5 0 0 1 1.016-.104c2.65 0 4.8 2.1 4.8 4.692a4.744 4.744 0 0 1-5.303 4.659q.555.67 1.247 1.2");
}

.vi5-a9b2c {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.882 16.922C6.235 14.15 8.837 12 11.99 12c3.22 0 5.86 2.24 6.127 5.092a8.3 8.3 0 0 1-1.28 1.026q.037-.27.038-.546c0-2.447-2.188-4.424-4.885-4.424s-4.884 1.977-4.884 4.424c0 .14.009.282.023.414a8 8 0 0 1-1.247-1.064");
}

</style>
