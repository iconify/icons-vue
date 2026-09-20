<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vzffklbwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-outline-sharp" /></template>
<style>
.vzffklbwm {
  fill: currentColor;
  d: path("M11 13H5v-2h6V5h2v6h6v2h-6v6h-2z");
}

</style>
