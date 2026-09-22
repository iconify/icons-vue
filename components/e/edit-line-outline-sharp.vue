<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0rig9bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:edit-line-outline-sharp" /></template>
<style>
.j0rig9bpy {
  fill: currentColor;
  d: path("M5 19h1.425L16.2 9.225L14.775 7.8L5 17.575zm-2 2v-4.25l14.625-14.6l4.2 4.275L7.25 21zM19 6.4L17.6 5zm-3.525 2.125l-.7-.725L16.2 9.225zM10.05 21l2-2H22v2z");
}

</style>
