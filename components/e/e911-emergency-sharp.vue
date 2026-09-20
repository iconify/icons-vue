<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vij5zxbzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:e911-emergency-sharp" /></template>
<style>
.vij5zxbzs {
  fill: currentColor;
  d: path("M5 20v-2h1.6L9 10h6l2.4 8H19v2zm6-12V3h2v5zm5.95 2.475L15.525 9.05l3.55-3.525l1.4 1.4zM18 15v-2h5v2zM7.05 10.475l-3.525-3.55l1.4-1.4l3.55 3.525zM1 15v-2h5v2z");
}

</style>
