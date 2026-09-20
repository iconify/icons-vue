<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="veuc6xbkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-align-center-outline-sharp" /></template>
<style>
.veuc6xbkf {
  fill: currentColor;
  d: path("m18 16l-4-4l4-4l1.4 1.4l-1.575 1.6H22v2h-4.175l1.575 1.6zm-7 4V4h2v16zm-5-4l-1.4-1.4L6.175 13H2v-2h4.175L4.6 9.4L6 8l4 4z");
}

</style>
