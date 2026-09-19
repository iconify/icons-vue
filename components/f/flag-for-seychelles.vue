<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="aesks5bgn"/><path class="g77yz7c4v"/><path class="t415-2v6b"/><path class="gs70997_e"/><path class="wi0_9kbbt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-seychelles" /></template>
<style>
.aesks5bgn {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M62 32c0-5.4-1.4-10.5-4-14.9L14.7 54.4L14 56c.1.1.3.2.4.3L61 39.7c.7-2.4 1-5 1-7.7");
}

.g77yz7c4v {
  fill: var(--svg-color--fcd856, #fcd856);
  d: path("M58 17.1C53.6 9.4 45.9 3.9 36.8 2.4L14 56z");
}

.gs70997_e {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.4 56.3c.1 0 .1.1.2.1l40.3-4.9c2.9-3.4 5-7.4 6.2-11.8z");
}

.t415-2v6b {
  fill: var(--svg-color--2872a0, #2872a0);
  d: path("M32 2c-8.2 0-15.6 3.3-21 8.6C5.5 16 2 23.6 2 32c0 9.5 4.4 18 11.4 23.5c.1.1.2.2.4.3c.1.1.2.1.3.2l.7-1.6l22.1-52C35.2 2.1 33.6 2 32 2");
}

.wi0_9kbbt {
  fill: var(--svg-color--699635, #699635);
  d: path("M32 62c9.1 0 17.3-4.1 22.8-10.5l-40.3 4.9c5 3.5 11 5.6 17.5 5.6");
}

</style>
