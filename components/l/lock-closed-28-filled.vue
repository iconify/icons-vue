<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x2zl1acxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-28-filled" /></template>
<style>
.x2zl1acxs {
  fill: currentColor;
  d: path("M14 2a5.5 5.5 0 0 1 5.5 5.5v2.509A3.75 3.75 0 0 1 23 13.75v8.5A3.75 3.75 0 0 1 19.25 26H8.75A3.75 3.75 0 0 1 5 22.25v-8.5a3.75 3.75 0 0 1 3.5-3.741V7.5A5.5 5.5 0 0 1 14 2m0 14.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m0-13a4 4 0 0 0-4 4V10h8V7.5a4 4 0 0 0-4-4");
}

</style>
