<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bt_i9i-if"/><path class="dc5din1xn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:balance" /></template>
<style>
.bt_i9i-if {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.748 4.5v39h12.797c6.466 0 11.707-5.241 11.707-11.706h0c0-2.994-1.124-5.726-2.973-7.796c-4.169 0-6.23-3.91-9.7-3.91c-4.534 0-6.394 3.72-11.83 3.72");
}

.dc5din1xn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.748 4.5h12.797c6.466 0 11.707 5.241 11.707 11.706h0c0 6.466-5.241 11.707-11.707 11.707c-5.74 0-9.012-4.105-12.797-4.105");
}

</style>
