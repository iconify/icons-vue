<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="co20d5our"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-share-sharp" /></template>
<style>
.co20d5our {
  fill: currentColor;
  d: path("M19.48 21q-.632 0-1.065-.434q-.434-.433-.434-1.072q0-.077.01-.144q.009-.067.028-.144l-2.198-1.321q-.206.163-.434.255q-.228.09-.503.09q-.632 0-1.066-.433t-.434-1.066t.434-1.067t1.066-.433q.275 0 .503.1t.434.265l2.217-1.315q-.154-.696.3-1.245t1.162-.55q.633 0 1.066.434T21 13.987t-.434 1.066q-.433.434-1.066.434q-.275 0-.513-.092q-.237-.091-.443-.254l-2.198 1.315q.039.16.039.287q0 .128-.039.288l2.198 1.315q.206-.163.434-.255q.228-.091.503-.091q.632 0 1.066.434q.434.433.434 1.066t-.434 1.066q-.433.434-1.066.434M14 8h4l-4-4l4 4l-4-4zM5 21V3h9.5L19 7.5v2.685q-.321-.074-.648-.107q-.327-.034-.66-.034q-2.765 0-4.728 1.96Q11 13.967 11 16.732q0 1.225.418 2.31q.419 1.086 1.144 1.959z");
}

</style>
