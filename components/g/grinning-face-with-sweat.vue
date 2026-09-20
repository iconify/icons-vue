<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><path class="twgr17b5c"/><path class="mu3hjibwp"/><path class="j97fxzb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:grinning-face-with-sweat" /></template>
<style>
.j97fxzb9u {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M35 11c0 2.762-2.238 5-5 5s-5-2.238-5-5s4-10 5-10s5 7.238 5 10");
}

.mu3hjibwp {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 23s3 1 9 1s9-1 9-1s-2 4-9 4s-9-4-9-4");
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.twgr17b5c {
  fill: var(--svg-color--664500, #664500);
  d: path("M28.457 17.797c-.06-.135-1.499-3.297-4.457-3.297s-4.397 3.162-4.457 3.297a.503.503 0 0 0 .755.605c.012-.009 1.262-.902 3.702-.902c2.426 0 3.674.881 3.702.901a.498.498 0 0 0 .755-.604m-12 0c-.06-.135-1.499-3.297-4.457-3.297s-4.397 3.162-4.457 3.297a.499.499 0 0 0 .754.605C8.31 18.393 9.559 17.5 12 17.5c2.426 0 3.674.881 3.702.901a.498.498 0 0 0 .755-.604M18 22c-3.623 0-6.027-.422-9-1c-.679-.131-2 0-2 2c0 4 4.595 9 11 9c6.404 0 11-5 11-9c0-2-1.321-2.132-2-2c-2.973.578-5.377 1-9 1");
}

</style>
