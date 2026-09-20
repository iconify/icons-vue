<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bko76hbpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:directions-32-filled" /></template>
<style>
.bko76hbpa {
  fill: currentColor;
  d: path("M12.816 2.318a4.5 4.5 0 0 1 6.364 0l10.499 10.5a4.5 4.5 0 0 1 0 6.363l-10.499 10.5a4.5 4.5 0 0 1-6.364 0L2.318 19.18a4.5 4.5 0 0 1 0-6.364zm5.391 6.476a1 1 0 1 0-1.414 1.414L18.586 12H16.5a4.5 4.5 0 0 0-4.5 4.5V21a1 1 0 0 0 2 0v-4.5a2.5 2.5 0 0 1 2.5-2.5h2.086l-1.793 1.793a1 1 0 0 0 1.414 1.414l3.5-3.5a1 1 0 0 0 0-1.414z");
}

</style>
