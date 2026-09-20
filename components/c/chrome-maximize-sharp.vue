<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fjo_zg3yw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-maximize-sharp" /></template>
<style>
.fjo_zg3yw {
  fill: currentColor;
  d: path("M4 20V4h16v16Z");
}

</style>
