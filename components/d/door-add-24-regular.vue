<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilq883wpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-add-24-regular" /></template>
<style>
.ilq883wpd {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m.25-10A2.25 2.25 0 0 1 20 4.25v7.248a6.5 6.5 0 0 0-1.5-.422V4.25a.75.75 0 0 0-.75-.75H6.25a.75.75 0 0 0-.75.75v15.5c0 .414.336.75.75.75h5.483a6.5 6.5 0 0 0 1.079 1.5H6.25A2.25 2.25 0 0 1 4 19.75V4.25A2.25 2.25 0 0 1 6.25 2zm-.25 11.999a.5.5 0 0 0-.5.5V17h-2.505a.5.5 0 0 0 0 1h2.506v2.504a.5.5 0 0 0 1 0V18h2.496a.5.5 0 0 0 0-1H18v-2.501a.5.5 0 0 0-.5-.5m-9-3.749a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3");
}

</style>
