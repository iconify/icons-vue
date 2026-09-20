<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="nj0tnd8yq"/><path class="ymqojl4ju"/><path class="t0f1viuxj"/><path class="me2dvfbra"/><path class="cj7hernii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-st-kitts-and-nevis" /></template>
<style>
.cj7hernii {
  fill: var(--svg-color--fff, #fff);
  d: path("m27.152 9.729l-2.074 1.513l-2.079-1.505l.798 2.439l-2.074 1.513l2.567-.005l.797 2.44l.789-2.443l2.567-.004l-2.08-1.505zM13.185 19.915l-2.074 1.513l-2.079-1.505l.798 2.439l-2.074 1.513l2.567-.005l.797 2.44l.789-2.443l2.567-.004l-2.08-1.505z");
}

.me2dvfbra {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5h-2.934L0 26.197V27a4 4 0 0 0 4 4h2.197L36 9.312V9a4 4 0 0 0-4-4");
}

.nj0tnd8yq {
  fill: var(--svg-color--009e49, #009e49);
  d: path("M4 5a4 4 0 0 0-4 4v15.323L26.496 5z");
}

.t0f1viuxj {
  fill: var(--svg-color--fcd116, #fcd116);
  d: path("M26.496 5L0 24.323v1.874L29.066 5zM8.767 31L36 11.186V9.312L6.197 31z");
}

.ymqojl4ju {
  fill: var(--svg-color--ce1126, #ce1126);
  d: path("M32 31a4 4 0 0 0 4-4V11.186L8.767 31z");
}

</style>
