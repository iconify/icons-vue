<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ft-w8lybs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:cancel-presentation-sharp" /></template>
<style>
.ft-w8lybs {
  fill: currentColor;
  d: path("m9.4 16l2.6-2.6l2.6 2.6l1.4-1.4l-2.6-2.6L16 9.4L14.6 8L12 10.6L9.4 8L8 9.4l2.6 2.6L8 14.6zM2 20V4h20v16z");
}

</style>
