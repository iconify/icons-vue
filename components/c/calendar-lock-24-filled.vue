<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mz0ceeg3f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-lock-24-filled" /></template>
<style>
.mz0ceeg3f {
  fill: currentColor;
  d: path("M21 8.5v3.05A3.5 3.5 0 0 0 15 14v.05a2.5 2.5 0 0 0-2 2.45V21H6.25A3.25 3.25 0 0 1 3 17.75V8.5zM17.75 3A3.25 3.25 0 0 1 21 6.25V7H3v-.75A3.25 3.25 0 0 1 6.25 3zM16 15h-.5a1.5 1.5 0 0 0-1.5 1.5v5a1.5 1.5 0 0 0 1.5 1.5h6a1.5 1.5 0 0 0 1.5-1.5v-5a1.5 1.5 0 0 0-1.5-1.5H21v-1a2.5 2.5 0 0 0-5 0zm1.5-1a1 1 0 1 1 2 0v1h-2zm2 5a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

</style>
