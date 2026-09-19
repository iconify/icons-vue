<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eg3v59vuq"/><path class="c_a768uhc"/><path class="l82phjbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bubble2" /></template>
<style>
.c_a768uhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.936 16.946c4.542-2.3 11.72-1.71 12.112 1.402s-6.7 5.107-10.01 5.4c7.571-.13 9.166 1.294 9.043 3.75s-4.836 4.616-9.266 4.953");
}

.eg3v59vuq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.6 39.893c4.846 1.233 8.08.187 9.039-.42c.959-.606 1.955-.89 3.004-.684c1.43.281 2.889.446 4.357.446c10.217 0 18.5-7.097 18.5-15.85S34.217 7.532 24 7.532S5.5 14.63 5.5 23.384c0 4.227 1.908 8.354 5.474 11.256c1.507 1.226-1.426 3.696-3.374 5.253");
}

.l82phjbtv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.086 16.862c.616 3.841.729 15.589.729 15.589");
}

</style>
