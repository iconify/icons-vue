<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jcu0-pppt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-space-around-outline" /></template>
<style>
.jcu0-pppt {
  fill: currentColor;
  d: path("M2 4V2h20v2zm0 18v-2h20v2zM7 9V6h10v3zm0 9v-3h10v3z");
}

</style>
