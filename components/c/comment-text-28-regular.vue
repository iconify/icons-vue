<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="gu4-13-3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:comment-text-28-regular" /></template>
<style>
.gu4-13-3g {
  fill: currentColor;
  d: path("M3.5 6.75A2.25 2.25 0 0 1 5.75 4.5h16.5a2.25 2.25 0 0 1 2.25 2.25v10.5a2.25 2.25 0 0 1-2.25 2.25h-6.426l-6.928 4.998a.25.25 0 0 1-.396-.203V19.5H5.75a2.25 2.25 0 0 1-2.25-2.25zM5.75 3A3.75 3.75 0 0 0 2 6.75v10.5A3.75 3.75 0 0 0 5.75 21H7v3.296c0 1.427 1.616 2.254 2.774 1.419L16.309 21h5.941A3.75 3.75 0 0 0 26 17.25V6.75A3.75 3.75 0 0 0 22.25 3zm6.5 10.5h9a.75.75 0 0 0 0-1.5h-9a.75.75 0 0 0 0 1.5m-3-1.5h-2.5a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5m-2.5 3.5a.75.75 0 0 0 0 1.5h9a.75.75 0 0 0 0-1.5zm12 1.5a.75.75 0 0 1 0-1.5h2.5a.75.75 0 0 1 0 1.5z");
}

</style>
