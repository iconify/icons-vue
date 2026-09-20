<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="is5kijbdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:folder-check-sharp" /></template>
<style>
.is5kijbdb {
  fill: currentColor;
  d: path("M10.85 16.575L16.5 10.9l-1.4-1.4l-4.25 4.25l-2.125-2.125L7.3 13.05zM2 20V4h8l2 2h10v14z");
}

</style>
