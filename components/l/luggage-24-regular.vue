<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="www0b8jur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:luggage-24-regular" /></template>
<style>
.www0b8jur {
  fill: currentColor;
  d: path("M8.75 2a.75.75 0 0 0 0 1.5H9V5h-.75A3.25 3.25 0 0 0 5 8.25v9a3.25 3.25 0 0 0 2 3v1a.75.75 0 0 0 1.5 0v-.75h7v.75a.75.75 0 0 0 1.5 0v-1a3.25 3.25 0 0 0 2-3v-9A3.25 3.25 0 0 0 15.75 5H15V3.5h.25a.75.75 0 0 0 0-1.5zm4.75 1.5V5h-3V3.5zm-5.25 3h7.5c.966 0 1.75.784 1.75 1.75v9A1.75 1.75 0 0 1 15.75 19h-7.5a1.75 1.75 0 0 1-1.75-1.75v-9c0-.966.784-1.75 1.75-1.75M8 9.75A.75.75 0 0 1 8.75 9h6.5a.75.75 0 0 1 0 1.5h-6.5A.75.75 0 0 1 8 9.75");
}

</style>
