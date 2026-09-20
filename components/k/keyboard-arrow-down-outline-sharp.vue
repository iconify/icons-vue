<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xx8hedcya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:keyboard-arrow-down-outline-sharp" /></template>
<style>
.xx8hedcya {
  fill: currentColor;
  d: path("m12 15.4l-6-6L7.4 8l4.6 4.6L16.6 8L18 9.4z");
}

</style>
