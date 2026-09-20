<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jaigiibck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bolt-rounded" /></template>
<style>
.jaigiibck {
  fill: currentColor;
  d: path("M9 15H5.9q-.6 0-.888-.537t.063-1.038l7.475-10.75q.25-.35.65-.487t.825.012t.625.525t.15.8L14 10h3.875q.65 0 .913.575t-.163 1.075L10.4 21.5q-.275.325-.675.425t-.775-.075t-.587-.537t-.163-.788z");
}

</style>
