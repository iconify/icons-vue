<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="m0l8a678t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-text-28-filled" /></template>
<style>
.m0l8a678t {
  fill: currentColor;
  d: path("M2 6.75A3.75 3.75 0 0 1 5.75 3h16.5A3.75 3.75 0 0 1 26 6.75v10.5A3.75 3.75 0 0 1 22.25 21h-5.941l-6.535 4.715C8.616 26.55 7 25.723 7 24.295V21H5.75A3.75 3.75 0 0 1 2 17.25zm10.25 6.75h9a.75.75 0 0 0 0-1.5h-9a.75.75 0 0 0 0 1.5m-3-1.5h-2.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5m-2.5 3.5a.75.75 0 0 0 0 1.5h9a.75.75 0 0 0 0-1.5zm12 1.5h2.5a.75.75 0 0 0 0-1.5h-2.5a.75.75 0 0 0 0 1.5");
}

</style>
