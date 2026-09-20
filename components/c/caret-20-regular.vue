<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="f7jfp7y4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-20-regular" /></template>
<style>
.f7jfp7y4n {
  fill: currentColor;
  d: path("M13.293 5.25c.63-.63 1.707-.184 1.707.707V13.5a1.5 1.5 0 0 1-1.5 1.5H5.957c-.89 0-1.337-1.077-.707-1.707zm.707.707L5.957 14H13.5a.5.5 0 0 0 .5-.5z");
}

</style>
