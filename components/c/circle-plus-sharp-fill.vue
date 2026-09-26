<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pq3zhxbjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-plus-sharp-fill" /></template>
<style>
.pq3zhxbjs {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM10.8946 6.6054L10.8946 10.9L6.6 10.9L6.6 13.1L10.8946 13.1L10.8946 17.4054L13.0946 17.4054L13.0946 13.1L17.4 13.1L17.4 10.9L13.0946 10.9L13.0946 6.6054L10.8946 6.6054Z");
}

</style>
