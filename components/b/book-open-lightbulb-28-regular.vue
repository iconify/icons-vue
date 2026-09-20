<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f4izv3blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-lightbulb-28-regular" /></template>
<style>
.f4izv3blm {
  fill: currentColor;
  d: path("M23.791 24.794A1.5 1.5 0 0 1 22.321 26h-.641a1.5 1.5 0 0 1-1.471-1.206l-.16-.794h3.901zM11.5 4c1.005 0 1.904.456 2.5 1.173A3.24 3.24 0 0 1 16.5 4h7.75c.966 0 1.75.784 1.75 1.75v7.778a6 6 0 0 0-1.5-.983V5.75a.25.25 0 0 0-.25-.25H16.5a1.75 1.75 0 0 0-1.75 1.75v13.5c0 .966.784 1.75 1.75 1.75h1.542q.378.333.808.602l.18.898H16.5a3.24 3.24 0 0 1-2.5-1.173A3.24 3.24 0 0 1 11.5 24H3.75A1.75 1.75 0 0 1 2 22.25V5.75C2 4.784 2.784 4 3.75 4zM22 13a5 5 0 0 1 2.258 9.46l-.109.54h-4.3l-.108-.54A5 5 0 0 1 22 13M3.75 5.5a.25.25 0 0 0-.25.25v16.5c0 .138.112.25.25.25h7.75a1.75 1.75 0 0 0 1.75-1.75V7.25A1.75 1.75 0 0 0 11.5 5.5z");
}

</style>
