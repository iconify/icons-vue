<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aurd0fsyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:highlighter-size-5-outline-sharp" /></template>
<style>
.aurd0fsyr {
  fill: currentColor;
  d: path("m10.25 22.25l-8.5-8.5q-.275-.275-.275-.7t.275-.7l10.6-10.6q.275-.275.688-.275t.712.3l8.5 8.475q.275.275.275.7t-.275.7l-10.6 10.6q-.275.275-.7.275t-.7-.275");
}

</style>
