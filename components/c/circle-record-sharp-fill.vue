<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g3b6p42rc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-record-sharp-fill" /></template>
<style>
.g3b6p42rc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M23 12C23 17.937 17.937 23 12 23C6.063 23 1 17.937 1 12C1 6.063 6.063 1 12 1C17.937 1 23 6.063 23 12ZM17 12C17 14.6233 14.6233 17 12 17C9.3767 17 7 14.6233 7 12C7 9.3767 9.3767 7 12 7C14.6233 7 17 9.3767 17 12Z");
}

</style>
