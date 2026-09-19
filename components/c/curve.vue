<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t7sm94bui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:curve" /></template>
<style>
.t7sm94bui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.495 43.295a21.5 21.5 0 1 1 .368-38.405m3.561 3.957L21.66 20.034m21.56-3.458L27.153 28.068m17.694-1.628l-12.203 9.255");
}

</style>
