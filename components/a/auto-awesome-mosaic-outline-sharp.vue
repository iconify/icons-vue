<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kzxh6ub8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-awesome-mosaic-outline-sharp" /></template>
<style>
.kzxh6ub8g {
  fill: currentColor;
  d: path("M11 21H3V3h8zm-2-2V5H5v14zm4-8V3h8v8zm2-2h4V5h-4zm-2 12v-8h8v8zm2-2h4v-4h-4zm0-4");
}

</style>
