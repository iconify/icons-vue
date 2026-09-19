<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o24e2unzb"/><path class="z2vld4brg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-switzerland" /></template>
<style>
.o24e2unzb {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M10 11C3.373 11 0 15.925 0 22v22c0 6.075 3.373 11 10 11h44c6.627 0 10-4.925 10-11V22c0-6.075-3.373-11-10-11");
}

.z2vld4brg {
  fill: var(--svg-color--fff, #fff);
  d: path("M19 38h8v8h9v-8h8v-9h-8v-8h-9v8h-8z");
}

</style>
