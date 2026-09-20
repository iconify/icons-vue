<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-zjvwvhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:e911-emergency-outline" /></template>
<style>
.m-zjvwvhi {
  fill: currentColor;
  d: path("M5 20v-2h1.6l1.975-6.575q.2-.65.738-1.037T10.5 10h3q.65 0 1.188.388t.737 1.037L17.4 18H19v2zm3.7-2h6.6l-1.8-6h-3zM11 8V3h2v5zm5.95 2.475L15.525 9.05l3.55-3.525l1.4 1.4zM18 15v-2h5v2zM7.05 10.475l-3.525-3.55l1.4-1.4l3.55 3.525zM1 15v-2h5v2zm11 3");
}

</style>
