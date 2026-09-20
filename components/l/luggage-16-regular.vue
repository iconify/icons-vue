<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t7si-jblc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:luggage-16-regular" /></template>
<style>
.t7si-jblc {
  fill: currentColor;
  d: path("M5.334 1.5a.5.5 0 0 1 .5-.5h4.333a.5.5 0 0 1 0 1H10v1h1a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2v.5a.5.5 0 0 1-1 0V14H6v.5a.5.5 0 0 1-1 0V14a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2h1V2h-.166a.5.5 0 0 1-.5-.5M7 2v1h2V2zM5 4a1 1 0 0 0-1 1v7a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V5a1 1 0 0 0-1-1zm0 2.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5");
}

</style>
