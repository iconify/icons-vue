<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cql0wwbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:doom-2" /></template>
<style>
.cql0wwbzs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.568 11.598H4.5m36.932 0H43.5M13.846 25.005L6.568 30.47V11.598h7.278zm1.918-1.277l4.913 3.689l2.364-1.952V11.598h-7.277zm16.472 0l-4.913 3.689l-2.364-1.952V11.598h7.277zm9.196 6.742V11.598h-1.273L37.738 27.05l-2.312-15.452h-1.272v13.407m-12.696 4.057h5.084m-5.084 7.34h5.084m-3.951-7.34v7.34m2.818-7.34v7.34");
}

</style>
