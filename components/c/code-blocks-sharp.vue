<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbsr2ibtw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:code-blocks-sharp" /></template>
<style>
.mbsr2ibtw {
  fill: currentColor;
  d: path("m9.6 14.908l.708-.714L8.114 12l2.174-2.175l-.707-.713L6.692 12zm4.8 0L17.308 12L14.4 9.092l-.708.714L15.887 12l-2.195 2.194zM4 20V4h16v16z");
}

</style>
