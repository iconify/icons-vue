<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b6l8b8b4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:hexagon-sharp" /></template>
<style>
.b6l8b8b4i {
  fill: currentColor;
  d: path("m6.8 21l-5.2-9l5.2-9h10.4l5.2 9l-5.2 9z");
}

</style>
