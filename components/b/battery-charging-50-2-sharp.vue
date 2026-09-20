<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_ur5gfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-charging-50-2-sharp" /></template>
<style>
.pv_ur5gfj {
  fill: currentColor;
  d: path("M2 17V7h14.25l-1.6 2H10v6h5l-.35 2zm14.675 0l.7-4H14l4.8-6h.525l-.7 4H22l-4.8 6z");
}

</style>
