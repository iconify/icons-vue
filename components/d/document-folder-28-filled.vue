<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="j5r9qd21h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-folder-28-filled" /></template>
<style>
.j5r9qd21h {
  fill: currentColor;
  d: path("M6.75 2A2.75 2.75 0 0 0 4 4.75v4.683A3.7 3.7 0 0 1 5.75 9h3.922a3.75 3.75 0 0 1 2.651 1.098l5.829 5.829a.25.25 0 0 0 .176.073H20.5V4.75A2.75 2.75 0 0 0 17.75 2zM23 16.075a4 4 0 0 0-.75-.075h-.75V4.8A2.75 2.75 0 0 1 23 7.25zM3 12.75A2.75 2.75 0 0 1 5.75 10h3.922c.729 0 1.428.29 1.944.806l5.829 5.828c.234.234.552.366.883.366h3.922A2.75 2.75 0 0 1 25 19.75v2.5A3.75 3.75 0 0 1 21.25 26H6.75A3.75 3.75 0 0 1 3 22.25z");
}

</style>
