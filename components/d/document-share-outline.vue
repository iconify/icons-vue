<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uswq3bp4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-share-outline" /></template>
<style>
.uswq3bp4y {
  fill: currentColor;
  d: path("M6 20V4zm13.48 1q-.632 0-1.065-.434q-.434-.433-.434-1.072q0-.077.01-.144q.009-.067.028-.144l-2.198-1.321q-.206.163-.434.255q-.228.09-.503.09q-.632 0-1.066-.433t-.434-1.066t.434-1.067t1.066-.433q.275 0 .503.1t.434.265l2.217-1.315q-.154-.696.3-1.245t1.162-.55q.633 0 1.066.434T21 13.987t-.434 1.066q-.433.434-1.066.434q-.275 0-.513-.092q-.237-.091-.443-.254l-2.198 1.315q.039.16.039.287q0 .128-.039.288l2.198 1.315q.206-.163.434-.255q.228-.091.503-.091q.632 0 1.066.434q.434.433.434 1.066t-.434 1.066q-.433.434-1.066.434m-7.614 0H6.616q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3H14.5L19 7.5v2.564h-1V8h-4V4H6.616q-.231 0-.424.192T6 4.615v14.77q0 .23.192.423t.423.192h5.252z");
}

</style>
