<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tpd_htfgc"/><path class="e6n87th4k"/><path class="ftcs-dbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-maldives" /></template>
<style>
.e6n87th4k {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M14 8h36c-5-3.8-11.2-6-18-6S19 4.2 14 8m18 54c6.8 0 13-2.2 18-6H14c5 3.8 11.2 6 18 6");
}

.ftcs-dbkk {
  fill: var(--svg-color--fff, #fff);
  d: path("M43 49.6C34.6 48 28.3 40.7 28.3 32S34.6 16 43 14.4c-1.2-.2-2.4-.4-3.7-.4C29.2 14 21 22.1 21 32s8.2 18 18.3 18c1.3 0 2.5-.1 3.7-.4");
}

.tpd_htfgc {
  fill: var(--svg-color--699635, #699635);
  d: path("M2 32c0 9.8 4.7 18.5 12 24h36c7.3-5.5 12-14.2 12-24S57.3 13.5 50 8H14C6.7 13.5 2 22.2 2 32");
}

</style>
