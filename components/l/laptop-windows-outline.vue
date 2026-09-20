<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yq4npyolj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:laptop-windows-outline" /></template>
<style>
.yq4npyolj {
  fill: currentColor;
  d: path("M0 20v-2h4v-1q-.825 0-1.412-.587T2 15V5q0-.825.588-1.412T4 3h16q.825 0 1.413.588T22 5v10q0 .825-.587 1.413T20 17v1h4v2zm4-5h16V5H4zm0 0V5z");
}

</style>
