<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x2-2cfxjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:clover-28-filled" /></template>
<style>
.x2-2cfxjk {
  fill: currentColor;
  d: path("M7.75 2a5.75 5.75 0 1 0 0 11.5h5a.75.75 0 0 0 .75-.75v-5A5.75 5.75 0 0 0 7.75 2m0 24a5.75 5.75 0 0 1 0-11.5h5a.75.75 0 0 1 .75.75v5A5.75 5.75 0 0 1 7.75 26m12.5-24a5.75 5.75 0 0 1 0 11.5h-5a.75.75 0 0 1-.75-.75v-5A5.75 5.75 0 0 1 20.25 2m0 24a5.75 5.75 0 0 0 0-11.5h-5a.75.75 0 0 0-.75.75v5A5.75 5.75 0 0 0 20.25 26");
}

</style>
