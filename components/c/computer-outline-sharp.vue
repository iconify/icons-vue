<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxp8icnmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:computer-outline-sharp" /></template>
<style>
.bxp8icnmc {
  fill: currentColor;
  d: path("M1 21v-2h22v2zm1-3V3h20v15zm2-2h16V5H4zm0 0V5z");
}

</style>
