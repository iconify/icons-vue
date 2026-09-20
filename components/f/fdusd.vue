<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q1qpbdczs"/><path class="urjii0bqn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:fdusd" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.q1qpbdczs {
  fill: var(--svg-color--00e98d, #00e98d);
  d: path("M3.93 16.655h9.932V21H3.931z");
}

.urjii0bqn {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.07 3H9.516v10.552H20.07V9.828h-6.207V6.724h6.207z");
}

</style>
