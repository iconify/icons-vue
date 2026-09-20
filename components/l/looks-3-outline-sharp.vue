<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_0ruob_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-3-outline-sharp" /></template>
<style>
.l_0ruob_l {
  fill: currentColor;
  d: path("M9 17h6V7H9v2h4v2h-2v2h2v2H9zm-6 4V3h18v18zm2-2h14V5H5zm0 0V5z");
}

</style>
