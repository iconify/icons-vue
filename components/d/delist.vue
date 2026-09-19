<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zxmq4i3ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:delist" /></template>
<style>
.zxmq4i3ui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.284 9.855l8.89 5.176L35.56 4.5M12 14.228l10.797 10.441l8.538-4.64M36 23.509L25.438 33.683l-9.154-5.087M12 33.148L22.709 43.5l8.626-5.176");
}

</style>
