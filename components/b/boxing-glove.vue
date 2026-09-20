<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vs0e5spzh"/><path class="yb_q8aclz"/><path class="l5_65dbgg"/><path class="nodz8_b_x"/><path class="aqq1_qb4d"/><path class="xl4ocvp_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:boxing-glove" /></template>
<style>
.aqq1_qb4d {
  fill: var(--svg-color--db4437, #db4437);
  d: path("m75.4 88.4l-42.6-.7c22.4 9.3 42.6.7 42.6.7");
}

.l5_65dbgg {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M93.3 23.2c.3-.4.1-8.6-8-15.4c-6.5-5.5-27.7-6.2-39-5.4c-12.6.9-20.1 5.7-24.2 18.2c-3.7 11.5-1.1 32.9 2.5 46.9C28 81 31.7 86.4 32.4 87.7l43.1.8c8.7-11.4 29.7-33.6 28.2-54.7c-1-15.1-10-10.9-10.4-10.6");
}

.nodz8_b_x {
  fill: var(--svg-color--ea6d47, #ea6d47);
  d: path("M31.6 88.8c-.7 1.3 0 3 1.4 3.6c20 8.8 37.2 2.6 42.1.4c1.7-.8 2-3.2.4-4.2c0 0-.1 0-.1-.1c0 0-20.2 8.5-42.6-.7c-.6.1-1 .5-1.2 1");
}

.vs0e5spzh {
  fill: var(--svg-color--db4437, #db4437);
  d: path("M35 85.5s-5 .9-5.4 5c-1.3 13.4 1.1 29.2 2.8 31.6c2.2 3 24.1 9 38 2.6c7.6-3.5 6.9-5.9 6.8-9.6c-.2-12.4 5.1-23.4 0-26.7c-5-3.3-33.9-5-42.2-2.9");
}

.xl4ocvp_c {
  fill: var(--svg-color--a52714, #a52714);
  d: path("M93.3 23.2S89.5 27 88 30.8s-1.9 8.2-3.6 12s-3.4 4.8-5.8 4s-6.4-14.1-.1-20.6c4.4-4.5 8.4-6.1 11.4-5.3c2.2.5 3.4 2.3 3.4 2.3");
}

.yb_q8aclz {
  fill: var(--svg-color--f7cb4d, #f7cb4d);
  d: path("M33.8 113c.2 1.3.9 2.4 2 3.2c5.2 3.8 19.5 5.5 28.2 2.4c4.1-1.4 4.9-3.3 4.9-11.8c0-3.5-1.7-5.8-5-5.7c-13.1 1.9-22.2 0-27-1.6c-1.9-.6-3.9.8-3.9 2.9c0 3 .1 7 .8 10.6");
}

</style>
