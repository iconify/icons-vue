<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="aclbcf0pn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:book-open-microphone-28-regular" /></template>
<style>
.aclbcf0pn {
  fill: currentColor;
  d: path("M25.75 19.25a.75.75 0 0 1 .75.75a5 5 0 0 1-4.25 4.943v1.307a.75.75 0 0 1-1.5 0v-1.307A5 5 0 0 1 16.5 20a.75.75 0 0 1 1.5 0a3.5 3.5 0 1 0 7 0a.75.75 0 0 1 .75-.75M11.5 4c1.005 0 1.904.456 2.5 1.173A3.24 3.24 0 0 1 16.5 4h7.75c.966 0 1.75.784 1.75 1.75v12.52a1.74 1.74 0 0 0-1 .15V16.5c0-.66-.183-1.276-.5-1.803V5.75a.25.25 0 0 0-.25-.25H16.5a1.75 1.75 0 0 0-1.75 1.75v13.5a1.75 1.75 0 0 0 1.263 1.68c.256.577.6 1.106 1.016 1.57H16.5a3.24 3.24 0 0 1-2.5-1.173A3.24 3.24 0 0 1 11.5 24H3.75A1.75 1.75 0 0 1 2 22.25V5.75C2 4.784 2.784 4 3.75 4zM3.75 5.5a.25.25 0 0 0-.25.25v16.5c0 .138.112.25.25.25h7.75a1.75 1.75 0 0 0 1.75-1.75V7.25A1.75 1.75 0 0 0 11.5 5.5zM21.5 14a2.5 2.5 0 0 1 2.5 2.5V20a2.5 2.5 0 0 1-5 0v-3.5a2.5 2.5 0 0 1 2.5-2.5");
}

</style>
