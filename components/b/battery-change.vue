<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i42emihsk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-change" /></template>
<style>
.i42emihsk {
  fill: currentColor;
  d: path("m11.75 16.67l.714-.69l-.585-.603q-.183-.183-.281-.416q-.098-.234-.098-.48q0-.252.098-.495q.098-.244.28-.426l.95-.95q.324-.323.498-.737t.174-.867q0-.46-.174-.895q-.174-.436-.497-.759l-.604-.585l-.688.714l.56.579q.182.182.293.416t.11.505q0 .265-.101.49t-.283.406l-.925.95q-.324.323-.507.746q-.184.423-.184.883t.174.895t.497.758zM8.692 21q-.348 0-.578-.23t-.23-.578V5.288q0-.348.23-.578t.578-.23h1.616V3h3.384v1.48h1.616q.348 0 .578.23t.23.579v14.903q0 .349-.23.578q-.23.23-.578.23z");
}

</style>
