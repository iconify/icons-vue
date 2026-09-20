<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugfs2wb9x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-vert-005-sharp" /></template>
<style>
.ugfs2wb9x {
  fill: currentColor;
  d: path("M9 19h6V6H9v13Zm-2 3V4h3V2h4v2h3v18H7Z");
}

</style>
