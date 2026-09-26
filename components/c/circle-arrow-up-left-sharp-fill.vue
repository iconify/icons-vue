<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h29zzibek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-arrow-up-left-sharp-fill" /></template>
<style>
.h29zzibek {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM8 9L8 16L10 16L10 11.4141L14.5859 15.9998L15.9999 14.5858L11.4141 10L16 10L16 8L9 8C8.4477 8 8 8.4477 8 9Z");
}

</style>
