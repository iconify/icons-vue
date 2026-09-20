<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c25803yon"/><path class="roq1a4b6j"/><path class="kdrj59-wc"/><path class="ez_r2pboy"/><path class="eqvu04bjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-thailand" /></template>
<style>
.c25803yon {
  fill: var(--svg-color--a7122d, #a7122d);
  d: path("M0 26.518V27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-.482z");
}

.eqvu04bjy {
  fill: var(--svg-color--a7122d, #a7122d);
  d: path("M0 9.333V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v.333z");
}

.ez_r2pboy {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 9.181h36v4.485H0z");
}

.kdrj59-wc {
  fill: var(--svg-color--292648, #292648);
  d: path("M0 13.513h36v8.821H0z");
}

.roq1a4b6j {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 22.181h36v4.485H0z");
}

</style>
