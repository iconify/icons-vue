<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="rb582bc8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:keyboard-tab-20-filled" /></template>
<style>
.rb582bc8e {
  fill: currentColor;
  d: path("M17 4.75a.75.75 0 0 0-1.5 0v10.5a.75.75 0 0 0 1.5 0zm-8.47-.53a.75.75 0 0 0-1.06 1.06l3.97 3.97H2.75a.75.75 0 0 0 0 1.5h8.69l-3.97 3.97a.75.75 0 1 0 1.06 1.06l5.25-5.25a.75.75 0 0 0 0-1.06z");
}

</style>
