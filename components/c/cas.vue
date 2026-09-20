<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcegns-bw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cas" /></template>
<style>
.fcegns-bw {
  fill: var(--svg-color--0723a1, #0723a1);
  fill-rule: evenodd;
  d: path("M10.41 3H8.293v3.2a6.88 6.88 0 0 0-3.176 5.801a6.88 6.88 0 0 0 3.176 5.8V21h2.115v-2.301a6.9 6.9 0 0 0 3.18 0V21h2.117v-3.198q.572-.367 1.059-.834v1.916h2.117V5.647h-2.117v1.388a7 7 0 0 0-1.06-.834V3h-2.117v2.303a6.9 6.9 0 0 0-3.179.001zm6.355 9a4.765 4.765 0 1 0-9.53 0a4.765 4.765 0 0 0 9.53 0");
}

</style>
