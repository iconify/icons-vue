<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tcn3-mefn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-autofit-width-dotted-24-regular" /></template>
<style>
.tcn3-mefn {
  fill: currentColor;
  d: path("M6.78 18.72a.75.75 0 0 1-1.06 1.06l-2.5-2.5a.75.75 0 0 1 0-1.06l2.5-2.5a.75.75 0 0 1 1.06 1.06l-1.97 1.97zM20 11.25a.75.75 0 0 1-1.5 0v-5a.75.75 0 0 0-.75-.75H6.25a.75.75 0 0 0-.75.75v5a.75.75 0 0 1-1.5 0v-5A2.25 2.25 0 0 1 6.25 4h11.5A2.25 2.25 0 0 1 20 6.25zm-10.5 5.5a.75.75 0 0 1-.75.75h-1a.75.75 0 0 1 0-1.5h1a.75.75 0 0 1 .75.75m3.5 0a.75.75 0 0 1-.75.75h-.5a.75.75 0 0 1 0-1.5h.5a.75.75 0 0 1 .75.75m4 0a.75.75 0 0 1-.75.75h-1a.75.75 0 0 1 0-1.5h1a.75.75 0 0 1 .75.75m3.832-.474a.75.75 0 0 1-.052 1.004l-2.5 2.5a.75.75 0 0 1-1.06-1.06l1.97-1.97l-1.97-1.97a.75.75 0 0 1 1.06-1.06l2.5 2.5z");
}

</style>
