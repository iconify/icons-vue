<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vrjrc8b7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-21-9-sharp" /></template>
<style>
.vrjrc8b7q {
  fill: currentColor;
  d: path("M2 17V7h20v10z");
}

</style>
