<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="s33lhq4vg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lightbulb-person-28-filled" /></template>
<style>
.s33lhq4vg {
  fill: currentColor;
  d: path("M5 11a9 9 0 1 1 14.79 6.89a3 3 0 0 0-.397.404A8.96 8.96 0 0 0 14 16.5a8.96 8.96 0 0 0-5.393 1.794a3 3 0 0 0-.398-.404A8.98 8.98 0 0 1 5 11m9 7a7.47 7.47 0 0 1 4.837 1.768L18.54 21H9.46l-.296-1.232A7.47 7.47 0 0 1 14 18m-4.181 4.5l.242 1.008A3.25 3.25 0 0 0 13.22 26h1.558a3.25 3.25 0 0 0 3.16-2.492l.242-1.008zM11.5 11a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0M14 7a4 4 0 1 0 0 8a4 4 0 0 0 0-8");
}

</style>
