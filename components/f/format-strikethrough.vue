<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uj8dkh-iv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:format-strikethrough" /></template>
<style>
.uj8dkh-iv {
  fill: currentColor;
  d: path("M10 19h4v-3h-4zM5 4v3h5v3h4V7h5V4zM3 14h18v-2H3z");
}

</style>
