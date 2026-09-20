<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo9m4eehz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-2-dashes-solid-24-filled" /></template>
<style>
.eo9m4eehz {
  fill: currentColor;
  d: path("M3 7a1 1 0 0 0 0 2h3a1 1 0 0 0 0-2zm7.5 0a1 1 0 0 0 0 2h3a1 1 0 1 0 0-2zM18 7a1 1 0 1 0 0 2h3a1 1 0 1 0 0-2zM3 15a1 1 0 1 0 0 2h18a1 1 0 1 0 0-2z");
}

</style>
