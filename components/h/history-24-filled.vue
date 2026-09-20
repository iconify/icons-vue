<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbzditbrm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:history-24-filled" /></template>
<style>
.nbzditbrm {
  fill: currentColor;
  d: path("M12 5a7 7 0 1 1-6.946 6.124a1 1 0 1 0-1.984-.248Q3 11.43 3 12a9 9 0 1 0 4-7.484V4a1 1 0 0 0-2 0v3a1 1 0 0 0 1 1h3a1 1 0 0 0 0-2h-.608A6.97 6.97 0 0 1 12 5m1 3a1 1 0 1 0-2 0v4a1 1 0 0 0 1 1h2.5a1 1 0 1 0 0-2H13z");
}

</style>
