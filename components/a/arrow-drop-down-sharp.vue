<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gkpvchb-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-drop-down-sharp" /></template>
<style>
.gkpvchb-b {
  fill: currentColor;
  d: path("m12 15l-5-5h10z");
}

</style>
