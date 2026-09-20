<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pvcxuh0bt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrows-more-up-rounded" /></template>
<style>
.pvcxuh0bt {
  fill: currentColor;
  d: path("M13.143 17.856Q13 17.713 13 17.5V9H4.5q-.213 0-.356-.144T4 8.499t.144-.356T4.5 8h8.692q.343 0 .576.232t.232.576V17.5q0 .213-.144.356t-.357.144t-.356-.144m4-3.98Q17 13.731 17 13.519v-8.5H8.5q-.213 0-.356-.144T8 4.52t.144-.356t.356-.144h8.692q.344 0 .576.233t.232.575v8.692q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
