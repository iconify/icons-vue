<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymth7t47l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:card-ui-info-24-regular" /></template>
<style>
.ymth7t47l {
  fill: currentColor;
  d: path("M16 9a7 7 0 1 1 0 14a7 7 0 0 1 0-14m0 1.5a5.5 5.5 0 1 0 0 11a5.5 5.5 0 0 0 0-11m0 5.25a.75.75 0 0 1 .75.75v2a.75.75 0 0 1-1.5 0v-2a.75.75 0 0 1 .75-.75M13.75 2A3.25 3.25 0 0 1 17 5.25v2.813a8 8 0 0 0-1.5-.046V5.25a1.75 1.75 0 0 0-1.75-1.75h-8.5A1.75 1.75 0 0 0 3.5 5.25v8.5c0 .966.784 1.75 1.75 1.75h2.768q-.016.248-.018.5q.002.508.064 1H5.25A3.25 3.25 0 0 1 2 13.75v-8.5A3.25 3.25 0 0 1 5.25 2zM16 12.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2M8.75 9a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1 0-1.5zm4-3.5a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1 0-1.5z");
}

</style>
