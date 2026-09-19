<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmyxa7ijf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-view-sidebar" /></template>
<style>
.jmyxa7ijf {
  fill: currentColor;
  d: path("M16 20H2V4h14zm2-12h4V4h-4zm0 12h4v-4h-4zm0-6h4v-4h-4z");
}

</style>
