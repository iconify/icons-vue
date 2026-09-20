<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hpvt4ackw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:area-chart-sharp" /></template>
<style>
.hpvt4ackw {
  fill: currentColor;
  d: path("m21 16l-9.4-7.35l-3.975 5.475L3 10.5V7l4 3l5-7l5 4h4zM3 20v-7l5 4l4-5.5l9 7.025V20z");
}

</style>
