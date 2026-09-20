<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1qw01bzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-more-down" /></template>
<style>
.s1qw01bzr {
  fill: currentColor;
  d: path("M6 20V10h1v9h9v1zm4-3.98v-10h1v9h9v1z");
}

</style>
