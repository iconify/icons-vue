<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1w6ljbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-garage-24-filled" /></template>
<style>
.r1w6ljbxr {
  fill: currentColor;
  d: path("M13.456 2.534a2.25 2.25 0 0 0-2.912 0l-6.75 5.728A2.25 2.25 0 0 0 3 9.977v9.273c0 .966.784 1.75 1.75 1.75H6.5v-6.25c0-.966.784-1.75 1.75-1.75h7.5c.966 0 1.75.784 1.75 1.75V21h1.75A1.75 1.75 0 0 0 21 19.25V9.977c0-.66-.29-1.288-.794-1.715zM16 21H8v-2.5h8zm0-4H8v-2.25a.25.25 0 0 1 .25-.25h7.5a.25.25 0 0 1 .25.25z");
}

</style>
