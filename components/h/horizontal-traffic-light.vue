<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dn7v39b6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:horizontal-traffic-light" /></template>
<style>
.dn7v39b6n {
  fill: currentColor;
  d: path("M47 17H17C8.75 17 2 23.75 2 32s6.75 15 15 15h30c8.25 0 15-6.749 15-15c0-8.25-6.75-15-15-15M13.25 39.5a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15m18.75 0a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15m18.75 0a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15");
}

</style>
