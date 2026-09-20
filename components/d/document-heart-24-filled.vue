<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcctyobuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-heart-24-filled" /></template>
<style>
.qcctyobuq {
  fill: currentColor;
  d: path("M12 2v6a2 2 0 0 0 2 2h6v10a2 2 0 0 1-2 2H9.49l3.17-3.17a4.467 4.467 0 0 0-5.645-6.87A4.47 4.47 0 0 0 4 11.235V4a2 2 0 0 1 2-2zm1.5.5V8a.5.5 0 0 0 .5.5h5.5zM7.015 22.75a.75.75 0 0 1-.53-.22l-4.41-4.408a3.467 3.467 0 1 1 4.904-4.903l.036.036l.036-.036a3.467 3.467 0 1 1 4.902 4.903L7.545 22.53a.75.75 0 0 1-.53.22");
}

</style>
