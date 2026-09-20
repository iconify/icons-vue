<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":308};
const content = `<path class="r7b8ixnch"/><path class="f3--4sbgo"/><path class="oo6h-xbst"/><path class="vuvu2p-4o"/><path class="t64g3hb5i"/><path class="pnsb6fv-r"/><path class="yljepntgr"/><path class="se6gn1b9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:aws-elastic-cache" /></template>
<style>
.f3--4sbgo {
  fill: var(--svg-color--19486f, #19486F);
  d: path("M128 0L0 99.591l127.175 15.813L256 99.596z");
}

.oo6h-xbst {
  fill: var(--svg-color--1f5b99, #1F5B99);
  d: path("M128 0L0 63.591v36.005l128-38.155z");
}

.pnsb6fv-r {
  fill: var(--svg-color--5294cf, #5294CF);
  d: path("M128 0v61.441l128 38.155V63.591z");
}

.r7b8ixnch {
  fill: var(--svg-color--99bce3, #99BCE3);
  d: path("M.822 207.604L128 307.2l127.179-99.596l-127.183-15.812z");
}

.se6gn1b9x {
  fill: var(--svg-color--5294cf, #5294CF);
  d: path("M128 200.054l55.467-8.125v-76.037l-55.467-8z");
}

.t64g3hb5i {
  fill: var(--svg-color--1f5b99, #1F5B99);
  d: path("M128 200.054l-55.467-8.125v-76.037l55.467-8l1.309 2.532l-.138 87.099z");
}

.vuvu2p-4o {
  fill: var(--svg-color--1f5b99, #1F5B99);
  d: path("M0 243.609l128 63.59v-61.441L0 207.608z");
}

.yljepntgr {
  fill: var(--svg-color--5294cf, #5294CF);
  d: path("M128 245.758V307.2l128-63.591v-36z");
}

</style>
