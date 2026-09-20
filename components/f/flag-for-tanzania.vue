<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="j9_zgyb2e"/><path class="ae3bji93a"/><path class="n_to0abdg"/><path class="idh9jgebh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-tanzania" /></template>
<style>
.ae3bji93a {
  fill: var(--svg-color--00a3dd, #00a3dd);
  d: path("M32 31a4 4 0 0 0 4-4V11.33L9.479 31z");
}

.idh9jgebh {
  fill: var(--svg-color--fbd035, #fbd035);
  d: path("M26.456 5L0 24.627v2.011L29.468 5zM9.479 31L36 11.33V9.318L6.467 31z");
}

.j9_zgyb2e {
  fill: var(--svg-color--1eb53a, #1eb53a);
  d: path("M4 5a4 4 0 0 0-4 4v15.627L26.456 5z");
}

.n_to0abdg {
  fill: var(--svg-color--141414, #141414);
  d: path("M32 5h-2.532L0 26.638V27a4 4 0 0 0 4 4h2.467L36 9.318V9a4 4 0 0 0-4-4");
}

</style>
