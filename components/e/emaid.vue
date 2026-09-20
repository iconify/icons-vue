<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q6k7psgur"/><path class="yfn42xsqa"/><path class="x_61pfv7s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:emaid" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q6k7psgur {
  fill: var(--svg-color--99bce3, #99bce3);
  d: path("m16.8 9.042l-2.4 1.362v5.514L4.2 9.936v2.568c0 .636.336 1.218.882 1.542L16.8 21z");
}

.x_61pfv7s {
  fill: var(--svg-color--2a5789, #2a5789);
  d: path("m12.3 11.73l-2.4-1.5l9.9-5.97v13.716c0 .588-.288 1.14-.768 1.47L16.8 21V9.042z");
}

.yfn42xsqa {
  fill: var(--svg-color--5892cd, #5892cd);
  d: path("M14.4 15.918v-2.994l-4.5-2.688l9.9-5.982l-2.136-1.062a1.8 1.8 0 0 0-1.698.042L4.2 9.936z");
}

</style>
