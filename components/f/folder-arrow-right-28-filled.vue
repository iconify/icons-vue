<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="n3s9sumbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:folder-arrow-right-28-filled" /></template>
<style>
.n3s9sumbs {
  fill: currentColor;
  d: path("M2 6.75A3.75 3.75 0 0 1 5.75 3h3.672c.729 0 1.428.29 1.944.805L13.25 5.69l-2.944 2.945A1.25 1.25 0 0 1 9.422 9H2zm.004 3.75v9.75A3.75 3.75 0 0 0 5.754 24H14.5A7.5 7.5 0 0 1 26 14.401V9.75A3.75 3.75 0 0 0 22.25 6h-7.19l-3.695 3.695a2.75 2.75 0 0 1-1.944.805zM20.5 13a6.5 6.5 0 1 1 0 13a6.5 6.5 0 0 1 0-13m-4 6a.5.5 0 0 0 0 1h6.793l-2.147 2.146a.5.5 0 0 0 .708.708l3-3a.5.5 0 0 0 .146-.351v-.006a.5.5 0 0 0-.146-.35l-3-3a.5.5 0 0 0-.708.707L23.293 19z");
}

</style>
