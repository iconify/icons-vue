<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skam7pbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:charging-station-outline-sharp" /></template>
<style>
.skam7pbya {
  fill: currentColor;
  d: path("M11.5 17v-4h-2l3-6v4h2zM5 23V1h14v22zm2-3v1h10v-1zm0-2h10V6H7zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
