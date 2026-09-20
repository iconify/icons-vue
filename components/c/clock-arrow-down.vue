<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtsrv1lsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:clock-arrow-down" /></template>
<style>
.gtsrv1lsq {
  fill: currentColor;
  d: path("M3.188 17.313Q1 15.125 1 12t2.188-5.312T8.5 4.5t5.313 2.188T16 12t-2.187 5.313T8.5 19.5t-5.312-2.187M19.5 20L16 16.5l1.425-1.4l1.075 1.075V4h2v12.2l1.1-1.1l1.4 1.4zm-9-4.5l1.4-1.4l-2.4-2.425V8h-2v4.5z");
}

</style>
