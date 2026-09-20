<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2b_vfike"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-important-outline" /></template>
<style>
.y2b_vfike {
  fill: currentColor;
  d: path("m2 20l6-8l-6-8h13q.475 0 .9.213t.7.587L22 12l-5.4 7.2q-.275.375-.7.588T15 20zm4-2h9l4.5-6L15 6H6l4.5 6zm6.75-6");
}

</style>
