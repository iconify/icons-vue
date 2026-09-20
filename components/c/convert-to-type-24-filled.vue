<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="li-0e3abb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:convert-to-type-24-filled" /></template>
<style>
.li-0e3abb {
  fill: currentColor;
  d: path("M5.25 4C4.56 4 4 4.56 4 5.25V8a1 1 0 0 1-2 0V5.25A3.25 3.25 0 0 1 5.25 2H8a1 1 0 0 1 0 2zm0 16C4.56 20 4 19.44 4 18.75V16a1 1 0 1 0-2 0v2.75A3.25 3.25 0 0 0 5.25 22H8a1 1 0 1 0 0-2zM20 5.25C20 4.56 19.44 4 18.75 4H16a1 1 0 1 1 0-2h2.75A3.25 3.25 0 0 1 22 5.25V8a1 1 0 1 1-2 0zM18.75 20c.69 0 1.25-.56 1.25-1.25V16a1 1 0 1 1 2 0v2.75A3.25 3.25 0 0 1 18.75 22H16a1 1 0 1 1 0-2zm-12-12a1 1 0 0 1 1-1h8.5a1 1 0 0 1 1 1v1.5a1 1 0 1 1-2 0V9H13v6h1.25a1 1 0 1 1 0 2h-4.5a1 1 0 1 1 0-2H11V9H8.75v.5a1 1 0 1 1-2 0z");
}

</style>
