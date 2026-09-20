<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e07jyib1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-48-filled" /></template>
<style>
.e07jyib1a {
  fill: currentColor;
  d: path("M19.582 4.83a6.25 6.25 0 0 1 8.84 0l14.752 14.753a6.25 6.25 0 0 1 0 8.839L28.421 43.175a6.25 6.25 0 0 1-8.839 0L4.831 28.422a6.25 6.25 0 0 1 0-8.84z");
}

</style>
