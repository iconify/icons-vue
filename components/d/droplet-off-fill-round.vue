<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvuu_ibzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:droplet-off-fill-round" /></template>
<style>
.mvuu_ibzp {
  fill: currentColor;
  d: path("m2.707 2.293l19 19a.999.999 0 1 1-1.414 1.414l-2.847-2.847A8 8 0 0 1 4 14c.001-2.061.741-4.041 1.802-5.784L1.293 3.707a.999.999 0 1 1 1.414-1.414m16.929 14.101L8.263 5.021a25 25 0 0 1 1.992-1.905c.377-.323.76-.641 1.164-.93a1 1 0 0 1 1.162 0c.404.289.787.607 1.164.93a25 25 0 0 1 2.508 2.475c.989 1.132 1.874 2.365 2.548 3.712c1.103 2.207 1.587 4.699.835 7.091");
}

</style>
