<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wwmnocbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-link-24-regular" /></template>
<style>
.wwmnocbuo {
  fill: currentColor;
  d: path("M18.5 20a.5.5 0 0 1-.5.5h-4.229a5 5 0 0 1-.77 1.5H18a2 2 0 0 0 2-2V9.828a2 2 0 0 0-.586-1.414l-5.829-5.828A2.05 2.05 0 0 0 12.172 2H6a2 2 0 0 0-2 2v10h1.5V4a.5.5 0 0 1 .5-.5h6V8a2 2 0 0 0 2 2h4.5zm-5-15.379L17.378 8.5H14a.5.5 0 0 1-.5-.5zM5.75 15.75A.75.75 0 0 0 5 15l-.2.005A4 4 0 0 0 5 23l.102-.007A.75.75 0 0 0 5 21.5l-.164-.005A2.5 2.5 0 0 1 5 16.5l.102-.007a.75.75 0 0 0 .648-.743M13 19a4 4 0 0 0-4-4l-.102.007A.75.75 0 0 0 9 16.5l.164.005A2.5 2.5 0 0 1 9 21.5l-.102.007A.75.75 0 0 0 9 23l.2-.005A4 4 0 0 0 13 19m-4.25-.75h-3.5l-.102.007a.75.75 0 0 0 .102 1.493h3.5l.102-.007a.75.75 0 0 0-.102-1.493");
}

</style>
