<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blpc9q-9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:device-meeting-room-all-in-one-24-regular" /></template>
<style>
.blpc9q-9f {
  fill: currentColor;
  d: path("M12 6.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5M17.75 3A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75V6.25A3.25 3.25 0 0 1 6.25 3zM4.5 17.75c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75V16h-15zM6.25 4.5A1.75 1.75 0 0 0 4.5 6.25v8.25h15V6.25a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
