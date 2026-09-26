<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rx2t-v_0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-bar-chart-horizontal-end-sharp-fill" /></template>
<style>
.rx2t-v_0o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C17.937 1 23 6.0629 23 12C23 17.937 17.937 23 12 23C6.0629 23 1 17.937 1 12C1 6.0629 6.0629 1 12 1ZM12.3333 9L17 9L17 7L12.3333 7L12.3333 9ZM7 13L17 13L17 11L7 11L7 13ZM9.6667 17L17 17L17 15L9.6667 15L9.6667 17Z");
}

</style>
