<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s1csq5ich"/><path class="zjod_qbyn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:coinex-smart-chain" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s1csq5ich {
  fill: var(--svg-color--5f5fff, #5f5fff);
  d: path("M14.474 8.965a3.11 3.11 0 0 1 3.3 1.404a3.095 3.095 0 0 1-1.798 4.608a3.11 3.11 0 0 1-3.382-1.193a3.1 3.1 0 0 1-.57-1.79H9.276a5.84 5.84 0 0 0 1.19 3.538a5.873 5.873 0 0 0 9.683-.496a5.84 5.84 0 0 0-.732-7.035a5.865 5.865 0 0 0-6.987-1.19a5.9 5.9 0 0 1 2.044 2.154");
}

.zjod_qbyn {
  fill: var(--svg-color--17e5aa, #17e5aa);
  d: path("M9.526 15.035a3.11 3.11 0 0 1-3.3-1.404a3.095 3.095 0 0 1 1.797-4.609a3.11 3.11 0 0 1 3.383 1.192c.37.524.57 1.15.57 1.79h2.747a5.84 5.84 0 0 0-1.19-3.537a5.873 5.873 0 0 0-9.683.497a5.84 5.84 0 0 0 .733 7.035a5.865 5.865 0 0 0 6.986 1.19a5.9 5.9 0 0 1-2.043-2.154");
}

</style>
