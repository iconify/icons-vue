<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6ovf3b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-charging-80-2" /></template>
<style>
.t6ovf3b-g {
  fill: currentColor;
  d: path("M3.308 16.5q-.348 0-.578-.23t-.23-.578V8.308q0-.348.23-.578t.578-.23h12.154l-.812 1H12.5v7h2.154l-.177 1zm14.06 0l.603-3.712h-2.933L18.417 7.5h.217l-.604 3.712h2.933L17.585 16.5z");
}

</style>
