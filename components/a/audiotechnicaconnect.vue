<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ujkd5vbje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:audiotechnicaconnect" /></template>
<style>
.ujkd5vbje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.43 41.93L25.22 5.28a1.33 1.33 0 0 0-1.65-.71a1.25 1.25 0 0 0-.79.71L8.57 41.93a1.17 1.17 0 0 0 .82 1.51a1.3 1.3 0 0 0 .4.06h28.43a1.25 1.25 0 0 0 1.28-1.21a.9.9 0 0 0-.07-.36m-8.09-20.85l-8.7 22.42");
}

</style>
