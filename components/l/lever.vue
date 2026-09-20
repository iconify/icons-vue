<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v18qu9bqy"/><path class="jj02c76og"/><path class="o_cgs_c8r"/><path class="ehpsy2bkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lever" /></template>
<style>
.ehpsy2bkq {
  fill: var(--svg-color--7fdf00, #7fdf00);
  d: path("M17.513 19.875H21L16.584 12z");
}

.ft5dv1b6b {
  fill: none;
}

.jj02c76og {
  fill: var(--svg-color--b0b5bf, #b0b5bf);
  d: path("M18.823 4.125L3 19.875h6.998l8.831-15.75z");
}

.o_cgs_c8r {
  fill: var(--svg-color--5aa800, #5aa800);
  d: path("M12.151 19.875H21L16.584 12z");
}

.v18qu9bqy {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.056 4.125L3 19.875h6.998l8.831-15.75z");
}

</style>
