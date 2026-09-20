<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4vzg4mdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-20-outline" /></template>
<style>
.q4vzg4mdf {
  fill: currentColor;
  d: path("M16.5 22v-3H14l3.5-5v3H20zM8 22q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V2h4v2h2q.425 0 .713.288T17 5v7q-.525 0-1.025.088T15 12.35V6H9v12h2q0 1.15.4 2.175T12.525 22z");
}

</style>
