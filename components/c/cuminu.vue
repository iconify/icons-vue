<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dkc-a_bls"/><path class="owm-dkonu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cuminu" /></template>
<style>
.dkc-a_bls {
  fill: var(--svg-color--ffd9e6, #ffd9e6);
  d: path("m8.5 12l-4 2.5v-5z");
}

.ft5dv1b6b {
  fill: none;
}

.owm-dkonu {
  fill: var(--svg-color--ff1381, #ff1381);
  d: path("m9.66 10.5l3.09-2.29l3.09 2.29l3.66-2.625L12.75 3L6 7.875zm0 3l3.09 2.29l3.09-2.29l3.66 2.625L12.75 21L6 16.125z");
}

</style>
