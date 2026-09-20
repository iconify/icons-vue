<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypbo53bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:equal" /></template>
<style>
.ypbo53bfx {
  fill: currentColor;
  d: path("M5 16v-2h14v2zm0-6V8h14v2z");
}

</style>
