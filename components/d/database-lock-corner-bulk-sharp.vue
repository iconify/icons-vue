<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ti9y80bfd"/><path class="kb2-e_u1z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:database-lock-corner-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kb2-e_u1z {
  d: path("M4 6c0 .537.802 1.025 1.205 1.227c2.082 1.041 5.539 1.025 7.59 0c.357-.178.71-.398.97-.705c.123-.146.235-.325.235-.522a1 1 0 0 1 2 0c0 .676-.276 1.302-.708 1.814c-.436.514-1.003.902-1.602 1.202c-2.089 1.044-4.942 1.211-7.232.727c-1.337-.283-2.845-.86-3.75-1.929C2.273 7.299 2 6.677 2 6a1 1 0 0 1 2 0m-2 5a1 1 0 0 1 2 0c0 .197.112.376.235.522c.26.307.613.527.969.705C6.34 12.794 7.743 13 9 13a1 1 0 0 1 0 2c-1.578 0-3.268-.273-4.69-.984c-.599-.3-1.167-.688-1.602-1.202C2.276 12.302 2 11.676 2 11m18 4h1a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-8a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1h1a3 3 0 1 1 6 0m-4 0h2a1 1 0 0 0-2 0");
}

.ti9y80bfd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 16V6c0-.676.276-1.302.708-1.814c2.465-2.913 10.119-2.913 12.584 0C15.724 4.698 16 5.324 16 6v3a1 1 0 0 1-1 1h-5v9a1 1 0 0 1-1 1c-1.578 0-3.268-.274-4.69-.984c-.599-.3-1.166-.688-1.602-1.202C2.276 17.302 2 16.676 2 16");
}

</style>
