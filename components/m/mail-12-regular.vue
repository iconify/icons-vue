<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="wsj1bjbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-12-regular" /></template>
<style>
.wsj1bjbko {
  fill: currentColor;
  d: path("M3.5 3A1.5 1.5 0 0 0 2 4.5v3A1.5 1.5 0 0 0 3.5 9h5A1.5 1.5 0 0 0 10 7.5v-3A1.5 1.5 0 0 0 8.5 3zM3 4.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 .5.5v.17L6 5.956L3 4.67zm0 1.258l2.803 1.201a.5.5 0 0 0 .394 0L9 5.758V7.5a.5.5 0 0 1-.5.5h-5a.5.5 0 0 1-.5-.5z");
}

</style>
