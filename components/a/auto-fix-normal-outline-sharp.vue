<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iefh_fbib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:auto-fix-normal-outline-sharp" /></template>
<style>
.iefh_fbib {
  fill: currentColor;
  d: path("m20 7l-.95-2.05L17 4l2.05-.95L20 1l.95 2.05L23 4l-2.05.95L20 7ZM5.825 22.425l-4.25-4.25l12.6-12.6l4.25 4.25l-12.6 12.6ZM5.8 19.6l7.2-7.2l-1.4-1.4l-7.2 7.2l1.4 1.4Z");
}

</style>
