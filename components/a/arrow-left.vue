<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="krct6gfoo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:arrow-left" /></template>
<style>
.krct6gfoo {
  fill: currentColor;
  d: path("m14 17l-5-5l5-5z");
}

</style>
