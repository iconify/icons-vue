<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="grv7j-bde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:full-screen-minimize-16-regular" /></template>
<style>
.grv7j-bde {
  fill: currentColor;
  d: path("M11 4a1 1 0 0 0 1 1h1.5a.5.5 0 0 1 0 1H12a2 2 0 0 1-2-2V2.5a.5.5 0 0 1 1 0zm0 8a1 1 0 0 1 1-1h1.5a.5.5 0 0 0 0-1H12a2 2 0 0 0-2 2v1.5a.5.5 0 0 0 1 0zm-7-1a1 1 0 0 1 1 1v1.5a.5.5 0 0 0 1 0V12a2 2 0 0 0-2-2H2.5a.5.5 0 0 0 0 1zm1-7a1 1 0 0 1-1 1H2.5a.5.5 0 0 0 0 1H4a2 2 0 0 0 2-2V2.5a.5.5 0 0 0-1 0z");
}

</style>
