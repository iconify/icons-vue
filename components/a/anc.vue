<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dkobe9b5j"/><path class="ib0gpbc7c"/><path clip-rule="evenodd" class="c2lbeefca"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:anc" /></template>
<style>
.c2lbeefca {
  fill: var(--svg-color--5fce5f, #5FCE5F);
  fill-rule: evenodd;
  d: path("M14.525 8.216a3.125 3.125 0 1 0-5.05.001L12 12.437z");
}

.dkobe9b5j {
  fill: var(--svg-color--43b543, #43B543);
  d: path("M3.601 20.333c-1.53-.858-2.056-2.756-1.171-4.24L9.26 4.82c.884-1.484 2.733-2.012 4.264-1.155s2.056 2.756 1.172 4.24l-6.722 11.29C7.09 20.682 5.132 21.19 3.6 20.334");
}

.ft5dv1b6b {
  fill: none;
}

.ib0gpbc7c {
  fill: var(--svg-color--306a30, #306A30);
  d: path("M20.399 20.333c1.53-.858 2.056-2.756 1.171-4.24L14.737 4.83c-.885-1.484-2.73-2.022-4.26-1.165c-1.531.857-2.056 2.756-1.172 4.24l6.722 11.29c.884 1.485 2.842 1.994 4.373 1.137");
}

</style>
