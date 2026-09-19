<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mt-hg--9x"/><path class="a6z0o3b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:eufylife" /></template>
<style>
.a6z0o3b7r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.523 2.535a4.125 4.125 0 0 0-3.204 6.73h0l6.615 7.764l6.55-7.687l.033-.037l.032-.04h0a4.129 4.129 0 1 0-6.615-4.924a4.12 4.12 0 0 0-3.407-1.806Z");
}

.mt-hg--9x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24A21.5 21.5 0 1 1 24 2.5V24");
}

</style>
