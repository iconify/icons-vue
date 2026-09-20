<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ix_rdsbxl"/><path class="scjs81pcf"/><path class="jl2mgikhi"/><path class="yi9zo2bxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-timor-leste" /></template>
<style>
.ix_rdsbxl {
  fill: var(--svg-color--dc241f, #dc241f);
  d: path("M32 5H4a4 4 0 0 0-4 4v18a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4V9a4 4 0 0 0-4-4");
}

.jl2mgikhi {
  fill: var(--svg-color--141414, #141414);
  d: path("m1.296 6.053l-.002.001A4 4 0 0 0 0 9v18c0 1.166.499 2.216 1.296 2.947L16 18z");
}

.scjs81pcf {
  fill: var(--svg-color--ffc726, #ffc726);
  d: path("M16 18L1.296 29.947q.118.108.244.207L23.667 18L1.54 5.846a4 4 0 0 0-.244.207z");
}

.yi9zo2bxs {
  fill: var(--svg-color--fff, #fff);
  d: path("m4.761 19.01l.492 3.269l1.523-2.934l3.262.542l-2.32-2.355l1.523-2.934l-2.957 1.478l-2.32-2.355l.493 3.269L1.5 18.468z");
}

</style>
