<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="eblb022sy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-right-28-filled" /></template>
<style>
.eblb022sy {
  fill: currentColor;
  d: path("M25 2.75a.75.75 0 0 0-1.5 0v22.5a.75.75 0 0 0 1.5 0zM19.25 5A2.75 2.75 0 0 1 22 7.75v2.5A2.75 2.75 0 0 1 19.25 13H5.75A2.75 2.75 0 0 1 3 10.25v-2.5A2.75 2.75 0 0 1 5.75 5zm0 10A2.75 2.75 0 0 1 22 17.75v2.5A2.75 2.75 0 0 1 19.25 23h-8a2.75 2.75 0 0 1-2.75-2.75v-2.5A2.75 2.75 0 0 1 11.25 15z");
}

</style>
