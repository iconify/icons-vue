<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btzt_lbad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:check-small" /></template>
<style>
.btzt_lbad {
  fill: currentColor;
  d: path("m10 16.4l-4-4L7.4 11l2.6 2.6L16.6 7L18 8.4z");
}

</style>
