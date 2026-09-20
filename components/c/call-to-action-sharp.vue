<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjhur9baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:call-to-action-sharp" /></template>
<style>
.sjhur9baf {
  fill: currentColor;
  d: path("M6 17h12v-3H6zm-4 3V4h20v16z");
}

</style>
