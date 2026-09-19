<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rhj2-jbsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-west" /></template>
<style>
.rhj2-jbsm {
  fill: currentColor;
  d: path("m9 19l1.41-1.41L5.83 13H22v-2H5.83l4.59-4.59L9 5l-7 7z");
}

</style>
