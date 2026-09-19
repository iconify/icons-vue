<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xcil6cm3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:custom-crosshair" /></template>
<style>
.xcil6cm3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.019 45.129a21.5 21.5 0 0 1-17.148-17.15m42.256.001a21.5 21.5 0 0 1-17.143 17.147m-.006-42.255a21.5 21.5 0 0 1 17.151 17.156m-42.257-.013a21.5 21.5 0 0 1 17.15-17.143");
}

</style>
