<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snwv1qmfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-h4" /></template>
<style>
.snwv1qmfj {
  fill: currentColor;
  d: path("M3 17V7h2v4h4V7h2v10H9v-4H5v4zm15 0v-3h-5V7h2v5h3V7h2v5h2v2h-2v3z");
}

</style>
