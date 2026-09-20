<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="jldmbcuvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:ladder-simple-bold" /></template>
<style>
.jldmbcuvp {
  fill: currentColor;
  d: path("M192 20a12 12 0 0 0-12 12v28H76V32a12 12 0 0 0-24 0v192a12 12 0 0 0 24 0v-28h104v28a12 12 0 0 0 24 0V32a12 12 0 0 0-12-12m-12 64v32H76V84ZM76 172v-32h104v32Z");
}

</style>
