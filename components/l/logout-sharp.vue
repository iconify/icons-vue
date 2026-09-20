<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhi2gtjje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:logout-sharp" /></template>
<style>
.fhi2gtjje {
  fill: currentColor;
  d: path("M3 21V3h9v2H5v14h7v2zm13-4l-1.375-1.45l2.55-2.55H9v-2h8.175l-2.55-2.55L16 7l5 5z");
}

</style>
