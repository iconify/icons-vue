<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpoderofg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-horizontal-right-sharp" /></template>
<style>
.bpoderofg {
  fill: currentColor;
  d: path("M20 22V2h2v20zM8 17v-3h10v3zm-6-7V7h16v3z");
}

</style>
