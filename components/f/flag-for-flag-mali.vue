<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fohd6dqnc"/><path class="gq4nsy2sh"/><path class="t_rlincix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-mali" /></template>
<style>
.fohd6dqnc {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M22 10h20v44H22z");
}

.gq4nsy2sh {
  fill: var(--svg-color--137a08, #137a08);
  d: path("M10 10C3.373 10 0 14.925 0 21v22c0 6.075 3.373 11 10 11h12V10z");
}

.t_rlincix {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M54 10H42v44h12c6.627 0 10-4.925 10-11V21c0-6.075-3.373-11-10-11");
}

</style>
