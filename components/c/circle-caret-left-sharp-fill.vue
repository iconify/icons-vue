<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5sqdxj-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-left-sharp-fill" /></template>
<style>
.e5sqdxj-j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM6.5144 12.8742L15.5144 17.8742C16.1809 18.2445 17 17.7625 17 17L17 7C17 6.2375 16.1809 5.7555 15.5144 6.1258L6.5144 11.1258C5.8285 11.5068 5.8285 12.4932 6.5144 12.8742Z");
}

</style>
