<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rimjcrq-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-dismiss-24-filled" /></template>
<style>
.rimjcrq-p {
  fill: currentColor;
  d: path("M17.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m1.25-6.5A3.25 3.25 0 0 1 22 8.75v4.062A6.5 6.5 0 0 0 12.024 21H5.25A3.25 3.25 0 0 1 2 17.75V9.5h6.129a2.25 2.25 0 0 0 1.59-.66l3.342-3.34zm1.104 9.647a.5.5 0 0 0-.707 0L17.5 16.793l-1.646-1.646a.5.5 0 1 0-.707.707l1.646 1.646l-1.646 1.646a.5.5 0 1 0 .707.707l1.646-1.646l1.646 1.646a.5.5 0 1 0 .707-.707L18.208 17.5l1.646-1.646a.5.5 0 0 0 0-.707M8.129 3a2.25 2.25 0 0 1 1.59.66l1.531 1.53l-2.59 2.59a.75.75 0 0 1-.531.22H2V6.25A3.25 3.25 0 0 1 5.25 3z");
}

</style>
