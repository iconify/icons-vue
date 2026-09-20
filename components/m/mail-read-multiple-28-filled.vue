<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="t69q6ccbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-read-multiple-28-filled" /></template>
<style>
.t69q6ccbv {
  fill: currentColor;
  d: path("M13.348 2.685a.75.75 0 0 0-.696 0L4.199 7.117c-.387.203-.698.51-.906.876L13 13.15l9.707-5.157a2.24 2.24 0 0 0-.906-.876zM3 17.75V9.536l9.648 5.126a.75.75 0 0 0 .704 0L23 9.536v8.214A3.25 3.25 0 0 1 19.75 21H6.25A3.25 3.25 0 0 1 3 17.75M6.012 22a3.25 3.25 0 0 0 2.739 1.5h11.5c2.9 0 5.25-2.35 5.25-5.25v-7.5a3.25 3.25 0 0 0-1.5-2.74v10.24A3.75 3.75 0 0 1 20.25 22z");
}

</style>
