<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="umyr_gbgb"/><path class="d679wobfj"/><path class="uk0v5lbmu"/><path class="v1n0-4bow"/><path class="nuoxh_bdi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kalm" /></template>
<style>
.d679wobfj {
  fill: var(--svg-color--fcb82b, #fcb82b);
  d: path("M6.938 11.438a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.374");
}

.ft5dv1b6b {
  fill: none;
}

.nuoxh_bdi {
  fill: var(--svg-color--414141, #414141);
  d: path("M15.375 8.063h3.375l-5.625 6.187L18.75 21h-3.375L9.75 14.25z");
}

.uk0v5lbmu {
  fill: var(--svg-color--40d27e, #40d27e);
  d: path("M6.938 16.5a1.688 1.688 0 1 0 0-3.375a1.688 1.688 0 0 0 0 3.375");
}

.umyr_gbgb {
  fill: var(--svg-color--e6403b, #e6403b);
  d: path("M6.938 6.375a1.688 1.688 0 1 0 0-3.375a1.688 1.688 0 0 0 0 3.375");
}

.v1n0-4bow {
  fill: var(--svg-color--2ba5f8, #2ba5f8);
  d: path("M6.938 21a1.687 1.687 0 1 0 0-3.375a1.687 1.687 0 0 0 0 3.375");
}

</style>
