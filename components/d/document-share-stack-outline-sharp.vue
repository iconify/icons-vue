<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwh5zobfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-share-stack-outline-sharp" /></template>
<style>
.fwh5zobfn {
  fill: currentColor;
  d: path("M7.385 17v-6.956v.152V3zm-1 1V2H15.5L20 6.5v3.97q-.244-.091-.484-.155q-.241-.063-.516-.119V7h-4V3H7.385v14H11q.02.256.046.506q.027.25.081.494zm13.096 3q-.633 0-1.067-.434q-.433-.433-.433-1.072q0-.077.01-.144q.009-.067.028-.144l-2.198-1.321q-.206.163-.434.255q-.228.09-.503.09q-.632 0-1.066-.433t-.434-1.066t.434-1.067t1.066-.433q.275 0 .503.1t.434.265l2.217-1.315q-.154-.696.3-1.245t1.162-.55q.633 0 1.066.434T21 13.987t-.434 1.066q-.433.434-1.066.434q-.275 0-.513-.092q-.237-.091-.443-.254l-2.198 1.315q.039.16.039.287q0 .128-.039.288l2.198 1.315q.206-.163.434-.255q.228-.091.503-.091q.632 0 1.066.434q.434.433.434 1.066t-.434 1.066q-.433.434-1.066.434M3 21.385V7.539h1v12.846h8.096q.195.292.415.535t.485.465z");
}

</style>
