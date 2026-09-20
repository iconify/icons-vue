<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mbk03pb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:location-28-filled" /></template>
<style>
.mbk03pb3m {
  fill: currentColor;
  d: path("M6.575 5.075c4.1-4.1 10.75-4.1 14.85 0s4.1 10.75 0 14.85l-.01.01l-5.509 5.295a2.75 2.75 0 0 1-3.811-.002l-5.51-5.292l-.01-.011c-4.1-4.1-4.1-10.75 0-14.85M14 8.5a4 4 0 1 0 0 8a4 4 0 0 0 0-8");
}

</style>
