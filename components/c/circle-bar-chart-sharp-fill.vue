<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p69jomuhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-sharp-fill" /></template>
<style>
.p69jomuhj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM9 9.6667L9 17L7 17L7 9.6667L9 9.6667ZM13 7L13 17L11 17L11 7L13 7ZM17 12.3333L17 17L15 17L15 12.3333L17 12.3333Z");
}

</style>
