<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="iam1accfm"/><path class="tcck-7cfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:asd" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iam1accfm {
  fill: var(--svg-color--43dcf2, #43DCF2);
  d: path("M6.805 18.666H2L12.227 8.661a1.43 1.43 0 0 1 1.444-.233c.64.261.545.794.55 1.033v7.928h-1.666V10.7l-6.5 6.3H8.7z");
}

.tcck-7cfn {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.97 5.617l-5.749 5.828v2.222l6.11-6.111V17h-9.187l-.812-1.667l-3.521 3.333h13.52A1.666 1.666 0 0 0 21.999 17V6.584c.017-.206-.083-.706-.61-1.072c-.529-.367-1.167-.084-1.417.11z");
}

</style>
