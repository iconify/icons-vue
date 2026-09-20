<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gia4jdzmy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:eda-outline-sharp" /></template>
<style>
.gia4jdzmy {
  fill: currentColor;
  d: path("M7 12V2h2v10zm4 0V1h2v11zm4 4.075V3h2v11.9zM5 21h9.075l4.85-4.85l-7.175 4.175L8.5 16H5zm-2 2v-9h6.5l2.75 3.675L17 14.9l3.4-1.95l2.625 1.95l-8.1 8.1zm2-9H3V4h2zm0-2h10zm0 9h9.075z");
}

</style>
