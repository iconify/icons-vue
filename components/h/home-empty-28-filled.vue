<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="r3ruvdb4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-empty-28-filled" /></template>
<style>
.r3ruvdb4a {
  fill: currentColor;
  d: path("M12.592 3.498a2.25 2.25 0 0 1 2.816 0l7.75 6.217A2.25 2.25 0 0 1 24 11.47v11.28A2.25 2.25 0 0 1 21.75 25H6.25A2.25 2.25 0 0 1 4 22.75V11.47c0-.683.31-1.328.842-1.755z");
}

</style>
