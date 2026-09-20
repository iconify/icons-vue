<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hm45_qbyd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:card-ui-info-24-filled" /></template>
<style>
.hm45_qbyd {
  fill: currentColor;
  d: path("M16 9a7 7 0 1 1 0 14a7 7 0 0 1 0-14m0 6.75a.75.75 0 0 0-.75.75v2a.75.75 0 0 0 1.5 0v-2a.75.75 0 0 0-.75-.75M13.75 2A3.25 3.25 0 0 1 17 5.25v2.813A8 8 0 0 0 8.064 17H5.25A3.25 3.25 0 0 1 2 13.75v-8.5A3.25 3.25 0 0 1 5.25 2zM16 12.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2M5.75 9a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zm0-3.5a.75.75 0 0 0 0 1.5h7.5a.75.75 0 0 0 0-1.5z");
}

</style>
