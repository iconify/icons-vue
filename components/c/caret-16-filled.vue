<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jc7b79alk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:caret-16-filled" /></template>
<style>
.jc7b79alk {
  fill: currentColor;
  d: path("M12 4.957c0-.89-1.077-1.337-1.707-.707L4.25 10.293c-.63.63-.184 1.707.707 1.707H10.5a1.5 1.5 0 0 0 1.5-1.5z");
}

</style>
