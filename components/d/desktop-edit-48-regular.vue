<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="afl_9-4se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desktop-edit-48-regular" /></template>
<style>
.afl_9-4se {
  fill: currentColor;
  d: path("M32.134 7.5H8.25A1.75 1.75 0 0 0 6.5 9.25v23.5c0 .967.784 1.75 1.75 1.75h31.5a1.75 1.75 0 0 0 1.75-1.75V14.889l2.5-2.461V32.75A4.25 4.25 0 0 1 39.75 37H31v3.5h2.75a1.25 1.25 0 1 1 0 2.5h-19.5a1.25 1.25 0 0 1 0-2.5H17V37H8.25A4.25 4.25 0 0 1 4 32.75V9.25A4.25 4.25 0 0 1 8.25 5h26.346zM19.5 40.5h9V37h-9zM39.183 3.19a3.981 3.981 0 1 1 5.63 5.63L31.089 22.33a3 3 0 0 1-1.352.767l-3.234.838c-1.476.382-2.82-.961-2.437-2.437l.838-3.234a3 3 0 0 1 .767-1.352z");
}

</style>
