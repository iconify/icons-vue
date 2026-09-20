<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="b0nyedkcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-2-dashes-solid-20-filled" /></template>
<style>
.b0nyedkcd {
  fill: currentColor;
  d: path("M2.75 6a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zm6 0a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zm6 0a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zm-12 6a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5z");
}

</style>
