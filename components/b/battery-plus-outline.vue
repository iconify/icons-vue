<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jamoxkbgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-plus-outline" /></template>
<style>
.jamoxkbgj {
  fill: currentColor;
  d: path("M8 22q-.425 0-.712-.288T7 21V5q0-.425.288-.712T8 4h2V2h4v2h2q.425 0 .713.288T17 5v7q-.525 0-1.025.088T15 12.35V6H9v14h2.35q.2.575.488 1.075t.687.925zm8 0v-3h-3v-2h3v-3h2v3h3v2h-3v3z");
}

</style>
