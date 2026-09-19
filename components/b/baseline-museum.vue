<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9ihp5bhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-museum" /></template>
<style>
.z9ihp5bhr {
  fill: currentColor;
  d: path("M22 11V9L12 2L2 9v2h2v9H2v2h20v-2h-2v-9zm-6 7h-2v-4l-2 3l-2-3v4H8v-7h2l2 3l2-3h2z");
}

</style>
