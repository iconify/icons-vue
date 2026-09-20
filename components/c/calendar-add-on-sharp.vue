<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2o6ttbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:calendar-add-on-sharp" /></template>
<style>
.p2o6ttbvf {
  fill: currentColor;
  d: path("M17 22v-3h-3v-2h3v-3h2v3h3v2h-3v3zM3 20V4h3V2h2v2h6V2h2v2h3v8.1q-.5-.075-1-.075t-1 .075V10H5v8h7q0 .5.075 1t.275 1z");
}

</style>
