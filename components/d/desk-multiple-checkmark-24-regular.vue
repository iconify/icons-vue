<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbo-3gb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:desk-multiple-checkmark-24-regular" /></template>
<style>
.jbo-3gb4k {
  fill: currentColor;
  d: path("M11.022 7q.06.782.293 1.5H4.25a.75.75 0 0 0-.75.75V11h9.312a6.5 6.5 0 0 0 2.185 1.5H11v6.25A2.25 2.25 0 0 1 8.75 21h-4.5A2.25 2.25 0 0 1 2 18.75v-9.5A2.25 2.25 0 0 1 4.25 7zM19.5 20.25a.75.75 0 0 1-1.5 0v-7.271a6.5 6.5 0 0 0 1.5-.294zm-16-1.5c0 .414.336.75.75.75h4.5a.75.75 0 0 0 .75-.75V12.5h-6zm18.501-1a.75.75 0 0 1-1.499.036v-5.521a6.5 6.5 0 0 0 1.499-1.078zM7.25 14a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1 0-1.5zM17.5 1a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m3.354 3.146a.5.5 0 0 0-.707 0L16.5 7.793l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0 0-.708m-9.54.354q-.233.719-.293 1.5H4.629A2.25 2.25 0 0 1 6.75 4.5z");
}

</style>
