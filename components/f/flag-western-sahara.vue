<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="w1dgew86a"/><path class="snqx7pl7d"/><path class="ti19ytvcr"/><path class="ccbb66bwk"/><g class="qds75v3pv"><path class="knvefsz8s"/><path class="ifehyw16d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-western-sahara" /></template>
<style>
.ccbb66bwk {
  fill: var(--svg-color--c4111b, #c4111b);
  d: path("M1.129 6.223A3.98 3.98 0 0 0 0 9v18c0 1.08.433 2.057 1.129 2.777L12 18z");
}

.ifehyw16d {
  d: path("m19.13 20.132l1.478-1.057l1.467 1.073l-.548-1.732L23 17.353l-1.817-.014l-.556-1.73l-.575 1.724l-1.817-.006l1.462 1.079z");
}

.knvefsz8s {
  d: path("M17.894 18.033a3.47 3.47 0 0 1 2.817-3.405a3.467 3.467 0 1 0-.001 6.81a3.466 3.466 0 0 1-2.816-3.405");
}

.qds75v3pv {
  fill: var(--svg-color--c4111b, #c4111b);
}

.snqx7pl7d {
  fill: var(--svg-color--007a3d, #007a3d);
  d: path("M0 27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-4.5H0z");
}

.ti19ytvcr {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 13.5h36v9H0z");
}

.w1dgew86a {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5H4a4 4 0 0 0-4 4v4.5h36V9a4 4 0 0 0-4-4");
}

</style>
