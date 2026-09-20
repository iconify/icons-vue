<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fa-yinnzr"/><path class="hu0_b2b-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hedera-hashgraph" /></template>
<style>
.fa-yinnzr {
  fill: var(--svg-color--000, #000);
  d: path("M12 3a9 9 0 1 0 0 18a9 9 0 0 0 0-18");
}

.ft5dv1b6b {
  fill: none;
}

.hu0_b2b-o {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.659 15.893h-1.143v-2.43H9.485v2.43H8.342v-7.88h1.143v2.372h5.03V8.013h1.144zm-6.12-3.34h5.03v-1.255H9.54z");
}

</style>
