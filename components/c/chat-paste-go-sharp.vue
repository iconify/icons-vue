<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d-sxmebwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chat-paste-go-sharp" /></template>
<style>
.d-sxmebwz {
  fill: currentColor;
  d: path("m18 21l-1.4-1.4l1.575-1.6H14v-2h4.175L16.6 14.4L18 13l4 4zM7 10h8V8H7zm0 4h5v-2H7zm-4 7V4h16v7.075q-.25-.05-.5-.062T18 11q-2.525 0-4.262 1.75T12 17q0 .25.013.5t.062.5H6z");
}

</style>
