<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho4oa_b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:format-italic-sharp" /></template>
<style>
.ho4oa_b5z {
  fill: currentColor;
  d: path("M5 19v-2.5h4l3-9H8V5h10v2.5h-3.5l-3 9H15V19z");
}

</style>
