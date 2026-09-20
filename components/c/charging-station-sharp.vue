<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxsnc_twd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:charging-station-sharp" /></template>
<style>
.fxsnc_twd {
  fill: currentColor;
  d: path("M11.5 17v-4h-2l3-6v4h2zM5 23V1h14v22zm2-5h10V6H7z");
}

</style>
