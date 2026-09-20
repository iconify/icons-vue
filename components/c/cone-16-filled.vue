<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tclox5b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cone-16-filled" /></template>
<style>
.tclox5b2s {
  fill: currentColor;
  d: path("M8 15c-2.229 0-6-.421-6-2q0-.06.014-.117l.047-.2a.5.5 0 0 1 .036-.1l5.453-11.3a.52.52 0 0 1 .9 0l5.453 11.3a.5.5 0 0 1 .036.1l.047.2Q14 12.94 14 13c0 1.579-3.771 2-6 2");
}

</style>
