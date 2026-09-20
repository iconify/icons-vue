<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="qxc9bdqpe"/><path class="qgqgc2bry"/><path class="zcd4ocn4p"/><path class="bpnd5eb7m"/><path class="nhtv22w0o"/><path class="xhgthxbwq"/><path class="vp1jvb1ys"/><path class="yrj3c8buw"/><path class="q7y7d0akq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-uruguay" /></template>
<style>
.bpnd5eb7m {
  fill: var(--svg-color--eee, #eee);
  d: path("M16 9V5H4a4 4 0 0 0-4 4v10h36v-3H16v-4h20V9z");
}

.nhtv22w0o {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M13 12a5 5 0 1 0-10 0a5 5 0 0 0 10 0");
}

.q7y7d0akq {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M5.834 12.004a2.153 2.153 0 1 1 4.307-.001a2.153 2.153 0 0 1-4.307.001");
}

.qgqgc2bry {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 23h36v3H0z");
}

.qxc9bdqpe {
  fill: var(--svg-color--0038a8, #0038a8);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-1H0zm0-8h36v4H0z");
}

.vp1jvb1ys {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("m8 5.597l.633 4.041l2.569-3.183l-1.473 3.816l3.816-1.473l-3.183 2.569l4.041.633l-4.041.633l3.183 2.569l-3.816-1.473l1.473 3.816l-2.569-3.183L8 18.403l-.633-4.041l-2.569 3.183l1.473-3.816l-3.816 1.473l3.183-2.569L1.597 12l4.041-.633l-3.183-2.569l3.816 1.473l-1.473-3.816l2.569 3.183z");
}

.xhgthxbwq {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M12 12a4 4 0 1 0-8 0a4 4 0 0 0 8 0");
}

.yrj3c8buw {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M11 12a3 3 0 1 0-6 0a3 3 0 0 0 6 0");
}

.zcd4ocn4p {
  fill: var(--svg-color--0038a8, #0038a8);
  d: path("M36 9a4 4 0 0 0-4-4H16v4zm-20 3h20v4H16z");
}

</style>
