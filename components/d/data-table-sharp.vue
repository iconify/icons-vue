<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixpd-33ix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:data-table-sharp" /></template>
<style>
.ixpd-33ix {
  fill: currentColor;
  d: path("M3 8h18V4H3zm0 6h18v-4H3zm0 6h18v-4H3zM4 7V5h2v2zm0 6v-2h2v2zm0 6v-2h2v2z");
}

</style>
