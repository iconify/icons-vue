<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gqi2oibfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-align-offset-left-sharp-fill" /></template>
<style>
.gqi2oibfy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1C17.937 1 23 6.0629 23 12ZM15 10L15 17L17 17L17 10L15 10ZM11 7L11 16L13 16L13 7L11 7ZM7 7L7 11L9 11L9 7L7 7Z");
}

</style>
