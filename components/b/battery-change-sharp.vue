<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9fciab6k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-change-sharp" /></template>
<style>
.l9fciab6k {
  fill: currentColor;
  d: path("M7.885 21V4.48h2.423V3h3.384v1.48h2.424V21zm3.865-4.33l.714-.69l-.585-.603q-.183-.183-.281-.416q-.098-.234-.098-.48q0-.252.098-.495q.098-.244.28-.426l.95-.95q.324-.323.498-.737t.174-.867q0-.46-.174-.895q-.174-.436-.497-.759l-.604-.585l-.688.714l.56.579q.182.182.293.416t.11.505q0 .265-.101.49t-.283.406l-.925.95q-.324.323-.507.746q-.184.423-.184.883t.174.895t.497.758z");
}

</style>
