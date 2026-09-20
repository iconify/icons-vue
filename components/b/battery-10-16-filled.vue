<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hmat00bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:battery-10-16-filled" /></template>
<style>
.hmat00bwy {
  fill: currentColor;
  d: path("M14 6.5h-.5V6c0-1.103-.897-2-2-2H4c-1.103 0-2 .897-2 2v4c0 1.103.897 2 2 2h7.5c1.103 0 2-.897 2-2v-.5h.5a.5.5 0 0 0 .5-.5V7a.5.5 0 0 0-.5-.5M12 10a.5.5 0 0 1-.5.5H4a.5.5 0 0 1-.5-.5V6a.5.5 0 0 1 .5-.5h7.5a.5.5 0 0 1 .5.5z");
}

</style>
