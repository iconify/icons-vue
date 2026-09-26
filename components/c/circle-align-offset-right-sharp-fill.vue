<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff8cuy0tf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-right-sharp-fill" /></template>
<style>
.ff8cuy0tf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1C17.937 1 23 6.0629 23 12ZM7 13L7 17L9 17L9 13L7 13ZM11 8L11 17L13 17L13 8L11 8ZM15 7L15 14L17 14L17 7L15 7Z");
}

</style>
