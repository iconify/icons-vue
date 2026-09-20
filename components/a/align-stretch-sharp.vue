<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ei849gtbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-stretch-sharp" /></template>
<style>
.ei849gtbg {
  fill: currentColor;
  d: path("M7 10V4H2V2h20v2h-5v6zM2 22v-2h5v-6h10v6h5v2z");
}

</style>
