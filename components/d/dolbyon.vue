<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hp67ubc3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dolbyon" /></template>
<style>
.hp67ubc3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 10.53h3.8A13.47 13.47 0 0 1 21.77 24v0A13.47 13.47 0 0 1 8.3 37.47H4.5h0V10.53h0Zm39 26.94h-3.77A13.47 13.47 0 0 1 26.23 24h0a13.47 13.47 0 0 1 13.5-13.47h3.8v26.94h-.03Z");
}

</style>
