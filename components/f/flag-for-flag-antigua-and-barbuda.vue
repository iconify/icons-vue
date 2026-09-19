<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ub1so94pi"/><path id="SVGI7X80bnd" class="x6i2gjbwj"/><use href="#SVGI7X80bnd"/><path class="mtf2ybbgs"/><path class="tod7e2bph"/><path class="jn79jpbry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-antigua-and-barbuda" /></template>
<style>
.jn79jpbry {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m36.2 22.2l5-6.4l-6.4 5.1L37 13l-4 7.1l-.9-8.1l-1.1 8.1l-3.9-7.1l2.1 7.8l-6.4-5l5.1 6.4L20 20l7.1 4l-8.1.9l.4.1h25.2l-7.7-1l7.1-3.9z");
}

.mtf2ybbgs {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M50.5 25L56 14C50.5 6.7 41.8 2 32 2S13.5 6.7 8 14l5.5 11z");
}

.tod7e2bph {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.5 39L32 62l11.5-23z");
}

.ub1so94pi {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M56 14H8c-3.8 5-6 11.2-6 18c0 16.6 13.4 30 30 30s30-13.4 30-30c0-6.8-2.2-13-6-18");
}

.x6i2gjbwj {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M20.5 39h23l7-14h-37z");
}

</style>
