<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyo8-xp4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-rounded" /></template>
<style>
.kyo8-xp4g {
  fill: currentColor;
  d: path("M11.5 12.5h-5q-.213 0-.356-.144T6 11.999t.144-.356t.356-.143h5v-5q0-.213.144-.356T12.001 6t.356.144t.143.356v5h5q.213 0 .356.144t.144.357t-.144.356t-.356.143h-5v5q0 .213-.144.356t-.357.144t-.356-.144t-.143-.356z");
}

</style>
