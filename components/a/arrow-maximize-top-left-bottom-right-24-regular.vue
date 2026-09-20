<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="miz9m9bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-top-left-bottom-right-24-regular" /></template>
<style>
.miz9m9bnk {
  fill: currentColor;
  d: path("M12.25 4a.75.75 0 0 1 0 1.5H6.56L18.5 17.44v-5.69a.75.75 0 0 1 1.5 0v7.5a.75.75 0 0 1-.75.75h-7.5a.75.75 0 0 1 0-1.5h5.69L5.5 6.56v5.69a.75.75 0 0 1-1.5 0v-7.5A.75.75 0 0 1 4.75 4z");
}

</style>
