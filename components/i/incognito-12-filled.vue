<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="a8_5zj63w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:incognito-12-filled" /></template>
<style>
.a8_5zj63w {
  fill: currentColor;
  d: path("M8.75 6.5A2.25 2.25 0 1 1 6.515 9h-1.03a2.25 2.25 0 1 1-.116-1h1.262A2.25 2.25 0 0 1 8.75 6.5m-5.5 1a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5m5.5 0a1.25 1.25 0 1 0 0 2.5a1.25 1.25 0 0 0 0-2.5M7.382 1a1.5 1.5 0 0 1 1.342.83L10 4.385q.134.024.24.046a11 11 0 0 1 .375.082h.002a.5.5 0 0 1-.237.971h-.003q-.167-.04-.336-.073A21 21 0 0 0 6 5a21 21 0 0 0-4.042.412q-.169.034-.336.072l-.003.001a.5.5 0 0 1-.237-.97l.002-.001l.1-.024q.095-.022.275-.058q.106-.022.238-.046l1.28-2.557A1.5 1.5 0 0 1 4.617 1z");
}

</style>
