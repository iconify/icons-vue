<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="bq1tkd83j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:headphones-sound-wave-28-filled" /></template>
<style>
.bq1tkd83j {
  fill: currentColor;
  d: path("M14 13a.75.75 0 0 1 .75.75v12.5a.75.75 0 0 1-1.5 0v-12.5A.75.75 0 0 1 14 13m0-11c6.627 0 12 5.373 12 12v8a4 4 0 0 1-3.8 3.995L22 26h-.5a1 1 0 0 1-.993-.884L20.5 25v-8a1 1 0 0 1 .884-.993L21.5 16h3v-2c0-5.799-4.701-10.5-10.5-10.5S3.5 8.201 3.5 14v2h3a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1H6a4 4 0 0 1-4-4v-8C2 7.373 7.373 2 14 2m-3.75 14a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75m7.5 0a.75.75 0 0 1 .75.75v6.5a.75.75 0 0 1-1.5 0v-6.5a.75.75 0 0 1 .75-.75");
}

</style>
