<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gngncypfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-segment" /></template>
<style>
.gngncypfs {
  fill: currentColor;
  d: path("M9 18h12v-2H9zM3 6v2h18V6zm6 7h12v-2H9z");
}

</style>
