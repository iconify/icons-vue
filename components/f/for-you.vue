<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aizrrfb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:for-you" /></template>
<style>
.aizrrfb8d {
  fill: currentColor;
  d: path("M15.744 12.068q1.912-.316 3.487-.876V19.5q-1.423.598-3.42.972q-1.995.374-3.811.374t-3.812-.374t-3.419-.972v-8.308q1.575.56 3.487.876t3.744.317t3.744-.317m-1.457-7.97q.944.944.944 2.287t-.944 2.286T12 9.616T9.714 8.67t-.945-2.286t.944-2.287T12 3.154t2.286.944");
}

</style>
