<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="f46jzubvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-2-28-regular" /></template>
<style>
.f46jzubvp {
  fill: currentColor;
  d: path("M5 11a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1zm-3-.25A3.75 3.75 0 0 1 5.75 7h14.5A3.75 3.75 0 0 1 24 10.75V12h1a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-1v1.25A3.75 3.75 0 0 1 20.25 21H5.75A3.75 3.75 0 0 1 2 17.25zM5.75 8.5a2.25 2.25 0 0 0-2.25 2.25v6.5a2.25 2.25 0 0 0 2.25 2.25h14.5a2.25 2.25 0 0 0 2.25-2.25v-6.5a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
