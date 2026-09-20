<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w2o01bacc"/><path class="d2kgz-bpp"/><path class="e5bsgmjmf"/><path class="piqkgcbdc"/><path class="k-ex0t_ew"/><path class="k0o33x50z"/><path class="x608v9bgk"/><path class="uzf0xtgxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bullet-train" /></template>
<style>
.d2kgz-bpp {
  fill: var(--svg-color--d1d3d4, #d1d3d4);
  d: path("M3 35h33V6H21c-4 0-5 2-5 2l-4 6S0 19 0 24c0 4 6 6 6 6z");
}

.e5bsgmjmf {
  fill: var(--svg-color--231f20, #231f20);
  d: path("m14 35l2-3h20v3z");
}

.k-ex0t_ew {
  fill: var(--svg-color--269, #269);
  d: path("m6 30l-3 5h33v-5z");
}

.k0o33x50z {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("m20 30l4-6h12v6z");
}

.piqkgcbdc {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M0 23.999c0 4 6 6 6 6V17.125C3 19 0 21.499 0 23.999M6 30v-.001z");
}

.uzf0xtgxo {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("m25.902 10l.549-1c.303-.552.102-1-.451-1H16l-1.333 2z");
}

.w2o01bacc {
  fill: var(--svg-color--939598, #939598);
  d: path("M0 34h36v2H0z");
}

.x608v9bgk {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M26 8H16l-4 6h-.001h10.843c.477 0 1.108-.448 1.412-1l2.197-4c.303-.552.102-1-.451-1");
}

</style>
