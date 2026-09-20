<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ag3dq1bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dialpad-24-regular" /></template>
<style>
.ag3dq1bii {
  fill: currentColor;
  d: path("M12 17.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m0-5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.996 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m-9.992 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.996-5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.996 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m-9.992 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.996-5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.996 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m-9.992 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
