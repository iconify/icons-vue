<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i239t8qkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-2-sharp-fill" /></template>
<style>
.i239t8qkc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM9 12.3333L9 17L7 17L7 12.3333L9 12.3333ZM13 9.6667L13 17L11 17L11 9.6667L13 9.6667ZM17 7L17 17L15 17L15 7L17 7Z");
}

</style>
