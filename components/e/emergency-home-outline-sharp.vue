<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="odhndcueq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:emergency-home-outline-sharp" /></template>
<style>
.odhndcueq {
  fill: currentColor;
  d: path("M11.5 13.26h1V7.856h-1zm.934 1.962q.182-.181.182-.433t-.182-.434t-.434-.182t-.434.182t-.182.434t.182.433t.434.182t.434-.182M12 21.377L2.623 12L12 2.623L21.377 12zM12 20l8-8l-8-8l-8 8zm0-8");
}

</style>
