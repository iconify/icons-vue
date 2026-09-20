<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eq_ucrfsm"/><path class="ej768905c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lusd" /></template>
<style>
.ej768905c {
  fill: var(--svg-color--2eb6ea, #2eb6ea);
  d: path("M10.875 3H3v9.162C3.081 16.69 6.47 20.47 10.875 21v-2.55c-1.525-.362-3.012-1.508-3.185-3.88l2.514-.73c-.016.782.321 2.345 1.797 2.335s1.796-1.074 1.772-1.604c.056-.348-.22-1.19-1.772-1.785c-1.94-.742-3.688-2.155-3.688-4.072c0-2.065 1.24-2.846 2.562-3.24z");
}

.eq_ucrfsm {
  fill: var(--svg-color--745ddf, #745ddf);
  d: path("M13.688 21C17.847 20.206 21 16.39 21 12s-3.153-8.046-7.312-8.84v2.384c.848.342 1.67 1.028 2.409 2.31c0 .077-1.496 1.1-2.203 1.58c-.874-2.111-2.23-2.133-2.794-1.373c-.807 1.088.603 1.81 2.218 2.413c1.827.68 3.208 2.288 3.182 4.339c-.025 2.004-1.457 3.054-2.812 3.571z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
