<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pkmasib7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-down-sharp-fill" /></template>
<style>
.pkmasib7o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM9 7L9 14.3333L7 14.3333L7 7L9 7ZM13 7L13 17L11 17L11 7L13 7ZM17 7L17 11.6667L15 11.6667L15 7L17 7Z");
}

</style>
