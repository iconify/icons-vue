<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zruhqpb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:horizontal-align-left-sharp" /></template>
<style>
.zruhqpb6m {
  fill: currentColor;
  d: path("M3 20V4h2v16zm9-3l-5-5l5-5l1.4 1.4l-2.6 2.6H21v2H10.8l2.6 2.6z");
}

</style>
