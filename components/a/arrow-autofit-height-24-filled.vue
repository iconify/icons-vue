<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gftkyvo7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-height-24-filled" /></template>
<style>
.gftkyvo7b {
  fill: currentColor;
  d: path("M17 14a1 1 0 0 1 1 1v2.586l.793-.793a1 1 0 1 1 1.414 1.414l-2.5 2.5a1 1 0 0 1-1.414 0l-2.5-2.5a1 1 0 0 1 1.414-1.414l.793.793V15a1 1 0 0 1 1-1M11 4a1 1 0 1 1 0 2H6.5a.5.5 0 0 0-.5.5v11a.5.5 0 0 0 .5.5H11a1 1 0 1 1 0 2H6.5A2.5 2.5 0 0 1 4 17.5v-11A2.5 2.5 0 0 1 6.5 4zm5.37-.775a1 1 0 0 1 1.337.068l2.5 2.5a1 1 0 0 1-1.414 1.414L18 6.414V9a1 1 0 0 1-2 0V6.414l-.793.793a1 1 0 0 1-1.414-1.414l2.5-2.5z");
}

</style>
