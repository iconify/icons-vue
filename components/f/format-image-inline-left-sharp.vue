<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vwuq3mq6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-image-inline-left-sharp" /></template>
<style>
.vwuq3mq6i {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-4V7h10v10zM3 5V3h18v2zm12 12v-2h6v2z");
}

</style>
