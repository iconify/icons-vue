<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy3tgwc8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:download-done" /></template>
<style>
.xy3tgwc8b {
  fill: currentColor;
  d: path("m9.55 16l-5.675-5.675L5.3 8.9l4.25 4.25L18.7 4l1.425 1.425zM5 20v-2h14v2z");
}

</style>
