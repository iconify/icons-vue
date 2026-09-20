<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wdaw2sbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-settings-16-filled" /></template>
<style>
.wdaw2sbvl {
  fill: currentColor;
  d: path("M8 1a7 7 0 0 1 6.964 6.29a5.5 5.5 0 1 0-7.675 7.675a7 7 0 0 1-2.827-.926l-2.804.936a.5.5 0 0 1-.633-.633l.934-2.806A7 7 0 0 1 8 1m1.068 5.746a2 2 0 0 0 2.91.001l.325-.344c.297.14.577.316.835.519l-.126.422a2 2 0 0 0 1.456 2.52l.348.081a4.7 4.7 0 0 1 .01 1.017l-.46.118a2 2 0 0 0-1.43 2.478l.156.556q-.382.295-.823.498l-.337-.358a2 2 0 0 0-2.91-.002l-.325.345a4.3 4.3 0 0 1-.834-.518l.126-.423a2 2 0 0 0-1.456-2.52l-.35-.081a4.7 4.7 0 0 1-.01-1.017l.462-.118a2 2 0 0 0 1.43-2.478l-.156-.556a4.3 4.3 0 0 1 .822-.498zM10.5 9.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
