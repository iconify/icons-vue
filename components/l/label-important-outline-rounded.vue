<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4r6ow5vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:label-important-outline-rounded" /></template>
<style>
.k4r6ow5vt {
  fill: currentColor;
  d: path("M15 20H4q-.625 0-.9-.55t.1-1.05L8 12L3.2 5.6q-.375-.5-.1-1.05T4 4h11q.475 0 .9.212t.7.588l4.5 6q.4.525.4 1.2t-.4 1.2l-4.5 6q-.275.375-.7.588T15 20m-9-2h9l4.5-6L15 6H6l3.6 4.8q.4.525.4 1.2t-.4 1.2zm6.75-6");
}

</style>
