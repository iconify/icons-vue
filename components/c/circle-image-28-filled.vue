<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="hqdbx4b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:circle-image-28-filled" /></template>
<style>
.hqdbx4b8t {
  fill: currentColor;
  d: path("M17.293 19.768a1 1 0 0 1 1.414 0l4.75 4.749A3.24 3.24 0 0 1 21.75 25h-7.5c-.626 0-1.21-.177-1.706-.483zM21.75 11A3.25 3.25 0 0 1 25 14.25v7.5c0 .626-.177 1.21-.483 1.706l-4.75-4.749a2.5 2.5 0 0 0-3.535 0l-4.749 4.75A3.24 3.24 0 0 1 11 21.75v-7.5A3.25 3.25 0 0 1 14.25 11zM11 2a8 8 0 0 1 8 8h-4.75A4.25 4.25 0 0 0 10 14.25v3.686A8 8 0 0 1 11 2m9.5 12a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3");
}

</style>
