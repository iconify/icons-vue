<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ncug-_bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-center-vertical-28-filled" /></template>
<style>
.ncug-_bso {
  fill: currentColor;
  d: path("M14.25 26a.75.75 0 0 1-.75-.75V23H10a2.75 2.75 0 0 1-2.75-2.75v-2.5A2.75 2.75 0 0 1 10 15h3.5v-2H7.25a2.75 2.75 0 0 1-2.75-2.75v-2.5A2.75 2.75 0 0 1 7.25 5h6.25V2.75a.75.75 0 0 1 1.5 0V5h5.75a2.75 2.75 0 0 1 2.75 2.75v2.5A2.75 2.75 0 0 1 20.75 13H15v2h3a2.75 2.75 0 0 1 2.75 2.75v2.5A2.75 2.75 0 0 1 18 23h-3v2.25a.75.75 0 0 1-.75.75");
}

</style>
