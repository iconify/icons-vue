<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxoqgrqzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-reply-all-24-regular" /></template>
<style>
.bxoqgrqzy {
  fill: currentColor;
  d: path("M9.28 5.22a.75.75 0 0 1 0 1.06l-4.47 4.47l4.47 4.47a.75.75 0 1 1-1.06 1.06l-5-5a.75.75 0 0 1 0-1.06l5-5a.75.75 0 0 1 1.06 0m4 0a.75.75 0 0 1 0 1.06L9.56 10h3.69A7.75 7.75 0 0 1 21 17.75v.5a.75.75 0 0 1-1.5 0v-.5a6.25 6.25 0 0 0-6.25-6.25H9.56l3.72 3.72a.75.75 0 1 1-1.06 1.06l-5-5a.75.75 0 0 1 0-1.06l5-5a.75.75 0 0 1 1.06 0");
}

</style>
