<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1fnx2bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-signal-cellular-alt" /></template>
<style>
.p1fnx2bzc {
  fill: currentColor;
  d: path("M17 4h3v16h-3zM5 14h3v6H5zm6-5h3v11h-3z");
}

</style>
