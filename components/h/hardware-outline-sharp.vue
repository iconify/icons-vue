<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zyxp43etg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hardware-outline-sharp" /></template>
<style>
.zyxp43etg {
  fill: currentColor;
  d: path("M10.27 7H5.845q.289-1.325 1.357-2.162Q8.27 4 9.653 4h4.616v2.885L17.154 4h1v6.77h-1l-2.885-2.885V20h-4zm1 12h2v-6.48h-2zm0-7.5h2V5H9.653q-.657 0-1.238.253T7.41 6h3.86zm1 .5");
}

</style>
