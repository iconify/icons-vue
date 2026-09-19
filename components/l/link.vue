<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="z3p269btt"><path class="jga3unbdn"/><path class="zoezb4blw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:link" /></template>
<style>
.jga3unbdn {
  d: path("M36.1 41.5c1.2 1.2 1.3 3 .2 4.1L18.7 63.3c-1.1 1.1-2.9.9-4.1-.2L1 49.4c-1.2-1.2-1.3-3-.2-4.1l17.7-17.7c1.1-1.1 2.9-.9 4.1.2c1.2 1.2 1.3 3 .2 4.1L8.9 45.8c-1.1 1.1-.9 2.9.2 4.1l5 5c1.2 1.2 3 1.3 4.1.2L32 41.3c1.1-1.1 3-1 4.1.2M63 14.6c1.2 1.2 1.3 3 .2 4.1L45.6 36.4c-1.1 1.1-2.9.9-4.1-.2c-1.2-1.2-1.3-3-.2-4.1l13.8-13.8c1.1-1.1.9-2.9-.2-4.1l-5-5c-1.2-1.2-3-1.3-4.1-.2L31.9 22.7c-1.1 1.1-2.9.9-4.1-.2c-1.2-1.2-1.3-3-.2-4.1L45.3.7c1.1-1.1 2.9-.9 4.1.2z");
}

.z3p269btt {
  fill: var(--svg-color--94989b, #94989b);
}

.zoezb4blw {
  d: path("M44.5 19.5c1.2 1.2 1.3 3 .2 4.1L23.6 44.7c-1.1 1.1-2.9.9-4.1-.2c-1.2-1.2-1.3-3-.2-4.1l21.1-21.1c1.1-1.1 2.9-1 4.1.2");
}

</style>
