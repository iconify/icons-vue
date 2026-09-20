<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogsjily1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:domain-verification-outline-sharp" /></template>
<style>
.ogsjily1t {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h16V8H4zm6.95-1.45L7.4 13l1.45-1.45l2.1 2.1l4.2-4.2l1.45 1.45zM4 18V6z");
}

</style>
