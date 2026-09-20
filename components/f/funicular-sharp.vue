<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1po6berb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:funicular-sharp" /></template>
<style>
.v1po6berb {
  fill: currentColor;
  d: path("M1 23v-2l5-1.375V17H3V6H2V4h3V2h14v2h3v2h-1v9h-3v1.375L23 15v2zm8-4.175l6-1.65V15h-2v2H9zM5 12h6V6H5zm8-2h6V6h-6z");
}

</style>
